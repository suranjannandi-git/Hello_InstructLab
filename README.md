# InstructLab
Use Instruct Lab - ilab CLI commands to finetune/deploy models

### Command commands
initiate ilab 
```bash 
ilab init
```

download default model, and expect below output 
```bash 
ilab download
```
/Folders
/config.yaml
/models
/taxonomy
/data/chatlogs

<img width="572" alt="ilab download" src="https://github.com/suranjannandi-git/Hello_InstructLab/assets/85071786/bebf86ba-f5ba-4a2c-ab9e-9c0257776928">

get the endpoint 
```bash 
ilab serve
```
<img width="578" alt="ilab serve" src="https://github.com/suranjannandi-git/Hello_InstructLab/assets/85071786/cfa1bae0-db91-43ca-96eb-0b0229ee0808">
<img width="1392" alt="ilab server swagger" src="https://github.com/suranjannandi-git/Hello_InstructLab/assets/85071786/a167c7a7-6ec6-44cd-b864-3e28a11397f8">

call the chat api
```bash 
ilab chat
```
<img width="571" alt="ilab chat" src="https://github.com/suranjannandi-git/Hello_InstructLab/assets/85071786/6d0795a0-4976-4c6a-ba7b-51bda9077c5b">
