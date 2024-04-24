# Llama 3 Test
This is an attempt to get a Llama 3 model running on an AMD/Radeon machine, preferably with a Langchain sort of interface like Private GPT or something.

## Background
I tried to set up a Llama model with Private GPT a few weeks back on my primary development machine but it didn't have great support for AMD CPU/GPUs. This thing runs a Ryzen chip with a Radeon GPU. I wrestled with it for a while and then switched over to my M1 mac and it was relatively straightforward with few issues. Support for Apple Silicone architecture was already pretty decent. However, that machine is getting dated. My initial plan was to buy an Nvidia GeForce GPU to be able to run it on my main workstation. Although, I am planning a design for a scalable on-prem rack of GPUs and hard drives for increasingly large training and data storage efforts, I need to go ahead and start playing with agents now.

## Along Comes Llama 3
So I hear Llama 3 is preposterously fast and has good support for AMD. If that's the case, I'm going to be able to go ahead and move forward with the software and data side of things now and take some more time to plan the on-prem infrastructure and the Kubernetes cluster that will manage the machines as nodes eventually.

