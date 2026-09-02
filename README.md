# AI-Prompt-Injection-Security-Testing
## Project Overview
A Cybersecurity Red Team Project focused on studying and testing prompt injection vulnerabilities in a locally deployed AI assistant. The project uses Kali Linux, Ollama, and the Llama 3.2 Large Language Model (LLM) to conduct controlled security experiments using synthetic data.

## Project Environment
Testing was performed entirely in a controlled local environment using Kali Linux, Ollama, and Llama 3.2. Fake demonstration data was used throughout the experiments, without targeting real systems or confidential information.

## Testing & Methodology
The AI assistant was first tested with normal user queries to establish baseline behavior. It was then evaluated using different prompt injection scenarios, including instruction override, instruction replacement, role manipulation, fake authorization, and direct information extraction. The responses were recorded and analyzed to identify weaknesses and potential information disclosure.

## Key Findings
The testing showed that some prompt injection attempts were successfully blocked, while fake authorization and direct information extraction were able to influence the AI and cause it to disclose protected demonstration information. This demonstrated the potential security risks of prompt injection in AI systems handling sensitive information.

## Project Report
The complete project report, including the setup, testing methodology, prompt injection scenarios, results, analysis, and mitigation strategies, can be accessed below:


## Conclusion
The project demonstrated that prompt injection can influence AI behavior in unintended ways. While the AI blocked several attempted attacks, certain techniques successfully resulted in information disclosure. The findings highlight the importance of strong system instructions, input filtering, access controls, monitoring, and regular security testing for AI applications.

## Collaborators
Alishba Anwar

Alishba Mehar
## Author
Alishba Mehar

www.linkedin.com/in/alishba-mehar-3205b140b
