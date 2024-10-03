In this ComfyUI Workflow, custom nodes obtained via the Manager tool are utilized to place two characters in one image together. 
This method helps avoid the entanglement of multiple concepts that happens often in image generation. 
You will need to upload a mask image and to clear out the section of the image you want the concepts to appear in. 
Additionally, the workflow requires the user to use 3 positive prompts for the image, for the base and each concept. 
More concepts can be added in if necessary using the base of what is there. 
Each positive prompt can be weighted differently depending on how strong that prompt should be. 
I have had the best results having the weight on the overall base positive prompt lower than the others.
