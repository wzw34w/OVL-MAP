# OVL-MAP
OVL-MAP: An Online Visual Language Map Approach for Vision-and-Language Navigation in Continuous Environments


 ## Abstract
Vision-and-Language Navigation in Continuous Environments involves in agents that navigate in 3D continuous environments based on visual observations and natural language instructions. Effective navigation in VLN-CE requires a deep understanding of the environment, which is often supported by navigation maps. However, existing approaches predominantly focus on topological and semantic maps, which offers limited scene understanding and diminishes navigation performance, especially in complex or unknown environments.
To address these challenges, this paper proposes a new algorithm, OVL-MAP, which comprises two main components: an online vision-and-language map construction module and a waypoint prediction module. The vision-and-language map module leverages strong semantic priors to enhance the agent's understanding of the environment, while the waypoint prediction module identifies relevant map regions based on natural language instructions, generates sub-goal points, and uses the DD-PPO strategy to guide the agent's actions. Evaluations on the Robo-VLN and R2R-CE datasets demonstrate that OVL-MAP significantly improves navigation performance and exhibits stronger generalization in unknown environments.
## Notes
This repository is used to display the scientific results of the paper "Vision-and-Language Navigation Based on History-Aware CrossModal  Feature Fusion in Indoor Environment".
