# local-ai-setup
Setting up local AI at home. Technologies: Docker, Open WebUI, VS Code Continue extension, ...
  
  
Technologies used:  
-- ai/smollm2-vllm:135M  
-- ai/qwen3:0.6B-Q4_K_M  
-- ghcr.io/open-webui/open-webui:v0.8.12  
-- falcosecurity/falco  
-- Docker version: 29.2.0  
-- Docker Desktop: 4.60.0  
-- VS Code version: 1.119.0  
-- VS Code: Continue extension (1.2.22)  

  
Wishlisted technologies:  
-- GPT-OSS 20B  
-- Qwen3-Coder 32B  
-- Wazuh (security)  

    
## Local AI Setup  

Note:    
Content censor is required on github.  
Censor out private info!  

  
### Hardware specs:  
VRAM: 16 GB  
RAM:  32 GB  
Storage: 1TB SSD  
  
  
### Project Guidelines That Should Be Followed:  
⎯ Ban network access for docker containers, docker images (Source: --)
  
⎯ Docker Desktop run in Rootless Mode. Never run the containers as root. 
Create non-root users for containers. (Source: --)
  
⎯ Do not run containers with priviliged flag (Source: --)
  
⎯ Instead of Docker sockets use Docker volumes (Source: --)
  
⎯ Use Docker Secrets (and Docker Swarm), store the secrets in files. (Never Use The Simple Environment Variables). (Source: --)
  
⎯ If you can, create separate Docker networks for containers. Use Docker Compose Network Segmentation. (Source: --)
  
⎯ Disable Inter-Container Communication. Only use defined ports. If you can use localhost. (Source: --)
  
⎯ Handle file permission for the non-root user. Lock Down container capabilities. Drop All Capabilities, Add Back Only What You Need. Make Read-Only Filesystems, allow writes only where necessary. (Source: --)
  
⎯ Secure your base images (for Supply Chain Security). Pin Specific Image Versions. Use Multi-Stage Builds to Minimize Attack Surface (and attack vector). (Source: --)
  
⎯ Use Docker Compose Network Segmentation (Source: --)
  
⎯ If you can make Resource Limits (To Prevent DoS). Set memory and CPU limits. Use docker compose deployment mode. (Source: --)
  

--- ban network access (Source: --)  

--- logging to file or sending alerts to owner email (Source: --)  


  
### Project file structure:  
test . text . example .  
/Project_Root  
├── /src  
│──├── main.py  
│──└── utils.py  
├── /docs  
│──└── README.md  
│── /assets  
│──└── logo.png  
├── Readme2.md  
  

├── hidden folder (hidden)  
├── hidden  

  
test . text . example .  
/Project_Root  
├── /src  
│──├── main.py  
│──└── utils.py  
├── /docs  
│──└── README.md  
└── /assets  
    └── logo.png  
  
  
### Components currently in the project:
  
AI_1 --  
  
AI_2 --  
  
Open web UI  
  
Falco (security)  [ recommended to be used ]  
  
~ Connection to VS Code  
  
### Wishlisted AI -s / Wishlisted technologies to try:  
--   


  
### Local AI Setup steps, commands:  
-- 


  
### Local AI Setup in VSCode steps, commands:  
-- 
  
  
  
### Sources for this project:    
-- 

  