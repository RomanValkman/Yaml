**Prompt in YAML**

| NAME  	| PROMPT   	| DESCRIPTION  	|EXAMPLE   	|
|---	|---	|---	|---	|
| App creation   	|create deploy nginx server  	| Deployment Nginx server  	|  [ app.yaml](app.yaml)	|
| Readiness probe  	|  application on nginx readiness probe 	|Readiness probe   	|  [ app_liveness_probe.yaml](app_liveness_probe.yaml) 	|
|  Liveness probe 	|application on nginx liveness probe every 5 sec   	| Liveness probe every 5 sec  	|  [ app_readiness_probe.yaml](app_readiness_probe.yaml) |
