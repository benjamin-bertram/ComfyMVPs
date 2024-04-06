# Setting Up a Web Interface Using ComfyUI

To quickly set up a web interface using ComfyUI, follow these steps:

## 1.Clone or Download the Repository:
Clone or download the repository directly into the `custom_nodes` directory within ComfyUI.

## 2.Run the ComfyUI Server:
Execute `run_nvidia_gpu.bat` or `run_cpu.bat`.

## 3.Replace the Default Workflow:
Follow these steps to replace the default workflow with your own:

- Enable Dev Mode Options: Click on "Settings" in the ComfyUI interface to enable Dev Mode Options.
- 
- Generate Workflow JSON: Go back and click "Save (API Format)" to make a JSON for your workflow.
- 
- Replace Base Workflow: Replace web/js/base_workflow.json with your JSON to use your workflow.

![comfygen](https://github.com/wei30172/comfygen/assets/60259324/b0b4f0f7-01fa-488e-aca0-24c38de18b18)

## 4.Access the Web Interface:
Open your web browser and navigate to `http://<comfy_address>:<comfy_port>/<repository_name>` (e.g., http://127.0.0.1:8188/comfygen). 

# Project Screenshots
![comfygen](https://github.com/wei30172/comfygen/assets/60259324/8263c7ad-5492-4a3d-946a-575c4dcaed60)
![comfygen](https://github.com/wei30172/comfygen/assets/60259324/ac77c19a-1715-4b25-a948-7a293e19362b)
