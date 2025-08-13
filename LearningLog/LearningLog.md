# Learning log
## Previous work
During the second semester, I was working on another topic, mainly "different ways of creating soft shadows in raytracing using DirectX12". I sadly found that topic was a bit too complex and would take more time than I had so I decided to change topics to "Different ways of implementing Ambient Occlusion at runtime using Vulkan".  
This topic however also took more time than expected so I was not able to finish it during the semester and decided to go for the retake. 

## Topic discussion
As the semester came to an end when I changed, not much topic discussion was done, but I got the green light from my supervisor Alexander Deweppe.

## Research proposition
### Research question
For my research, I was planning to comparing 3 different types of generating ambient occlusion at runtime and see which took more memory and which had more of an impact on framerate. Therefore, my research questions were:  
 - "What form of Ambient Occlusion has the best result in terms of performance"
 - "What form of Ambient Occlusion has the best result in terms of VRAM and RAM usage"

### Hypotheses
    Before my hypotheses could be formed I had to do extensive research, the sources for this research can be found in my literature study.  

    [Hypotheses]
    -In terms of performance
        -"GTAO will perform better than HBAO and SSAO"
        -"HBAO will perform better than SSAO but worse than GTAO"
        -"SSAO will perform worse than GTAO and HBAO"
    -In terms of memory usage
        -"GTAO and HBAO will have the same memory usage in terms of RAM and are both better than SSAO"
        -"All 3 methods will have the same VRAM usage"

### Case study
For my case study I will have to follow these steps:  
    - Implement deferred rendering into pre-existing lightweight engine  
    - Implement all 3 methods of ambient occlusion into engine  
    - Measure performance and memory usage for all 3 methods  

    
## Experiment update
I realized that the looks of the ambient occlusion are, of course, also very important, therefore I have to update my experiment to take this into account.  

    [New hypotheses]  
    -In terms of looks
        -"GTAO will look better than HBAO and SSAO"
        -"HBAO will look better than SSAO but worse than HBAO"
        -"SSAO will look worse than GTAO and HBAO"
    -In terms of performance
        -"GTAO will perform better than HBAO and SSAO"
        -"HBAO will perform better than SSAO but worse than GTAO"
        -"SSAO will perform worse than GTAO and HBAO"
    -In terms of memory usage
        -"GTAO and HBAO will have the same memory usage in terms of RAM and are both better than SSAO"
        -"All 3 methods will have the same VRAM usage"
    
    [New case study steps]
    - Implement deferred rendering into pre-existing lightweight engine  
    - Implement all 3 methods of ambient occlusion into engine  
    - Measure performance and memory usage for all 3 methods 
    - Poll people for "best looking" method of AO

## Experiment design
### What are the concrete measurments that will be taken
    - Framerate in ms/frame for ao generation for each method
    - Ram usage for each method
    - Vram usage for each method
    - Poll for "best looking" method


## 18/05 - 25/05
    - Prepared pre-existing project for implementation of deferred rendering
    - Researched deferred rendering and different types of ambient occlusion
    - Created literature study

## 01/06 - 19/06
    - Implemented deferred rendering into pre-existing project
    - Continued to look for sources for general AO

## 04/07 - 15/07
    - Implemented multipass rendering for smoother experimentation
    - Researched multipass rendering

## 16/07 - 22/07
    - Implemented Screen Space Ambient Occlusion

## 22/07 - 30/07
    - Implemented Horizon Based Ambient Occlusion

## 31/07 - 1/08
    - Implemented Ground Truth Ambient Occlusion

## 02/08 - 04/08
    - Implemented time stamping method for benchmarking
    - Realised that an app called Renderdoc does this for you with higher quality
    
## 05/8 - 08/08
    - Prepared everything for experiments

## 09/08
    - Set up questionnaire and sent to as many people as possible

## 10/08 - 13/08
    - Took all measurments needed for second half of the experiment
