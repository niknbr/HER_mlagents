# Evaluating Hindsight Experience Replay with Reward Shaping on the Hallway Environment

To setup this project the following steps need to be taken:
1. Download and install the Unity Editor from  [website](https://store.unity.com/products/unity-personal)  
2. Setup Unity [ml-agents toolkit](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Readme.md).
3. Clone this repository
3. Replace the `UnitySDK/Assets/ML-Agents/Examples/Hallway/` environment in the Unity SDK under ml-agents with the one from this repository `Hallway/`
4. Open the downloaded Unity SDK under ml-agents from Unity Editor.
5. Double click the `HallwayLearningBrain` in the project pane under `Assets > ML-Agents > Examples > Hallway > Brains`
 
    ![Hallway_brain.png](https://www.dropbox.com/s/vk76zbkwr44hfxj/Hallway_brain.png?dl=0&raw=1 )

6. Update the settings of the brain as follows

    ![brainsettings.png](https://www.dropbox.com/s/lbadtrqee8iipuf/brainsettings.png?dl=0&raw=1)

7. Open the `Hallway` scene in projects pane under `Assets > ML-Agents > Examples > Hallway > Scenes` 

    ![Hallway_Scene.png](https://www.dropbox.com/s/2h123ns13rjsu7o/Hallway_Scene.png?dl=0&raw=1)

8. Double click the `Academy` under the `Heirarcy` pane

    ![Academy.png](https://www.dropbox.com/s/6kd8w491pxdrucc/Academy.png?dl=0&raw=1)

9. Check the `Control` button for the learning brain under the `Inspector` pane

    ![control_button.png](https://www.dropbox.com/s/xh22t5k9awb9ux4/control_button.png?dl=0&raw=1)

8. Open the jupyter notebook in this repository on an environment with pytorch installed
9. Execute the jupyter notebook and when promted Click the play button on unity editor
    ![play_button.png](https://www.dropbox.com/s/xuacrw5owi8rml5/play_button.png?dl=0&raw=1)

Once the connection is made to the unity environment, we can follow along the jupyter notebook to execute the algorithm.