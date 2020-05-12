# build_angular

	
	src/main/resources:
	static folder
	templates folder
	
	
	
	cd frontend
	npm install
	ng build --prod --deploy-url=/static/dist/ --aot
	
	
	import { environment } from '../../../../environments/environment.prod';
	var serverUrl = environment.serverUrl + '/<controller end point>';
	
