```bash
2025-07-10T17:04:57.584Z	Initializing build environment...
2025-07-10T17:05:04.577Z	Success: Finished initializing build environment
2025-07-10T17:05:04.781Z	Cloning repository...
2025-07-10T17:05:09.457Z	No build output detected to cache. Skipping.
2025-07-10T17:05:09.457Z	No dependencies detected to cache. Skipping.
2025-07-10T17:05:09.459Z	Detected the following tools from environment: 
2025-07-10T17:05:09.464Z	Executing user deploy command: npx wrangler deploy
2025-07-10T17:05:12.451Z	npm warn exec The following package was not found and will be installed: wrangler@4.24.0
2025-07-10T17:05:25.742Z	
2025-07-10T17:05:25.743Z	 ⛅️ wrangler 4.24.0
2025-07-10T17:05:25.743Z	───────────────────
2025-07-10T17:05:25.752Z	
2025-07-10T17:05:25.859Z	✘ [ERROR] Missing entry-point to Worker script or to assets directory
2025-07-10T17:05:25.859Z	
2025-07-10T17:05:25.860Z	  
2025-07-10T17:05:25.860Z	  If there is code to deploy, you can either:
2025-07-10T17:05:25.860Z	  - Specify an entry-point to your Worker script via the command line (ex: `npx wrangler deploy src/index.ts`)
2025-07-10T17:05:25.861Z	  - Or create a "wrangler.jsonc" file containing:
2025-07-10T17:05:25.861Z	  
2025-07-10T17:05:25.861Z	  ```
2025-07-10T17:05:25.861Z	  {
2025-07-10T17:05:25.862Z	    "name": "worker-name",
2025-07-10T17:05:25.862Z	    "compatibility_date": "2025-07-10",
2025-07-10T17:05:25.862Z	    "main": "src/index.ts"
2025-07-10T17:05:25.862Z	  }
2025-07-10T17:05:25.863Z	  ```
2025-07-10T17:05:25.863Z	  
2025-07-10T17:05:25.863Z	  
2025-07-10T17:05:25.863Z	  If are uploading a directory of assets, you can either:
2025-07-10T17:05:25.863Z	  - Specify the path to the directory of assets via the command line: (ex: `npx wrangler deploy --assets=./dist`)
2025-07-10T17:05:25.864Z	  - Or create a "wrangler.jsonc" file containing:
2025-07-10T17:05:25.864Z	  
2025-07-10T17:05:25.864Z	  ```
2025-07-10T17:05:25.865Z	  {
2025-07-10T17:05:25.865Z	    "name": "worker-name",
2025-07-10T17:05:25.865Z	    "compatibility_date": "2025-07-10",
2025-07-10T17:05:25.865Z	    "assets": {
2025-07-10T17:05:25.866Z	      "directory": "./dist"
2025-07-10T17:05:25.866Z	    }
2025-07-10T17:05:25.866Z	  }
2025-07-10T17:05:25.867Z	  ```
2025-07-10T17:05:25.867Z	  
2025-07-10T17:05:25.867Z	
2025-07-10T17:05:25.867Z	
2025-07-10T17:05:25.868Z	
2025-07-10T17:05:25.868Z	Cloudflare collects anonymous telemetry about your usage of Wrangler. Learn more at https://github.com/cloudflare/workers-sdk/tree/main/packages/wrangler/telemetry.md
2025-07-10T17:05:25.877Z	🪵  Logs were written to "/opt/buildhome/.config/.wrangler/logs/wrangler-2025-07-10_17-05-24_868.log"
2025-07-10T17:05:26.122Z	Failed: error occurred while running deploy command
```
