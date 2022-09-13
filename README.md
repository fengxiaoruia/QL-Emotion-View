宝塔配置
 location ^~/api/ {
	        proxy_pass http://43.132.148.139:8080/;
	    }
        