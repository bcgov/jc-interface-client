[![Lifecycle:Stable](https://img.shields.io/badge/Lifecycle-Stable-97ca00)](https://github.com/bcgov/jc-interface-client/)

# jc-interface-client


Using git subtree: 
	TODO

Generating Clients: 

	Prep: 
	1. Download the latest NSwagStudio: https://github.com/RicoSuter/NSwag/wiki/NSwagStudio

	Scripted version:
	1. Copy over the OAS3 specs from the JC-Interface project (private repo) into API References
	2. Run generate-jc-clients. It may take a while to run this script, let it run.

	Manual: 
	1. Open up NSwagStudio
	2. Load the NSwagConfig/*.nswag configurations
	3. Paste in the updated OpenAPI (OAS3.0) specification JSON from step 2
	4. Press Generate Outputs
	5. Goto CSharp Client tab
	6. Copy output into appropriate .cs file under Clients/
	7. Repeat for each client
	8. Run tests