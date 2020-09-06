#   			 Logstash 			->			 elastic search 	-> 						Kibana
##   port :    		9600							9200								5601/app/kibana	
		 (logstash/bin/logstash.conf)						 					update kibana.yml -> uncomment elasticsearch port	
		    	--input																
		    	--filter
			   --output
		 logstash -f logstash.conf			     elastic.bat							     kibana.bat				
											localhost:9200/_cat/indices?v			
											localhost:9200/{index}/_search	
