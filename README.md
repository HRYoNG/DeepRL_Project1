# Deep Reinforcement Project #1 - Udacity DeepRL Nanodegree course

1. Project Details

    ![image](https://user-images.githubusercontent.com/55370676/193630580-1698a5b8-53b7-4b1e-a31a-0f2e4e5f16ff.png)

   - Reward : +1 when collecting a yellow banana, and -1 when collecting a blue banana.

   - State Space : The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. 

   - Action Space :
    0 - move forward.
    1 - move backward.
    2 - turn left.
    3 - turn right.

   - Goal : Environment solved when getting an average score of +13 over 100 consecutive episodes.
  


2. Getting Started

    - File list  : ① Navigation.ipynb ② dqn_agent.py ③ model.py ④ checkpoint.pth(saved model weights)

    - Download the environment from one of the links below. You need only select the environment that matches your operating system:

        Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
        
        Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
        
        Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
        
        Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
        
        (For Windows users) Check out this link if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.
        

        (For AWS) If you'd like to train the agent on AWS (and have not enabled a virtual screen), then please use this link to obtain the environment.

    - Place the file in the course GitHub repository, in the p1_navigation/ folder, and unzip (or decompress) the file.


3. Instructions

   - Follow the instructions in Navigation.ipynb
   - Run the codes below '4. It's Your Turn!' in 'Navigation.ipynb' to check the trained agent.
   - 'dqn_agent.py' and 'model.py' should be included in the same project with 'Navigation.ipynb'.
   - Experiment results of the trained model was already recorded in the notebook files.
  
