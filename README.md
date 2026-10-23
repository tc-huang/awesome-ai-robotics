# awesome-ai-robotics

> [!NOTE]
> This list is currently being updated. The previous version is available in [README_old.md](README_old.md).

## Papers
### Imitation Learning Policies
- **Robomimic** (2021): What Matters in Learning from Offline Human Demonstrations for Robot Manipulation. [[Paper]](https://arxiv.org/abs/2108.03298) [[Code]](https://github.com/ARISE-Initiative/robomimic) [[Project]](https://robomimic.github.io/)
- **Diffusion Policy** (2023): Diffusion Policy: Visuomotor Policy Learning via Action Diffusion. [[Paper]](https://arxiv.org/abs/2303.04137) [[Code]](https://github.com/real-stanford/diffusion_policy) [[Project]](https://diffusion-policy.cs.columbia.edu/)
- **ACT** (2023): Learning Fine-Grained Bimanual Manipulation with Low-Cost Hardware. [[Paper]](https://arxiv.org/abs/2304.13705) [[Code]](https://github.com/tonyzhaozh/act) [[Project]](https://tonyzhaozh.github.io/aloha/)

### Vision-Language-Action Models
- **OpenVLA** (2024): OpenVLA: An Open-Source Vision-Language-Action Model. [[Paper]](https://arxiv.org/abs/2406.09246) [[Code]](https://github.com/openvla/openvla) [[Project]](https://openvla.github.io/)
- **π0** (2024): π0: A Vision-Language-Action Flow Model for General Robot Control. [[Paper]](https://arxiv.org/abs/2410.24164) [[Code]](https://github.com/Physical-Intelligence/openpi) [[Project]](https://www.pi.website/blog/pi0)
- **OpenVLA-OFT** (2025): Fine-Tuning Vision-Language-Action Models: Optimizing Speed and Success. [[Paper]](https://arxiv.org/abs/2502.19645) [[Code]](https://github.com/moojink/openvla-oft) [[Project]](https://openvla-oft.github.io/)
- **π0.5** (2025): π0.5: a Vision-Language-Action Model with Open-World Generalization. [[Paper]](https://arxiv.org/abs/2504.16054) [[Code]](https://github.com/Physical-Intelligence/openpi) [[Project]](https://www.pi.website/blog/pi05)
- **SmolVLA** (2025): SmolVLA: A Vision-Language-Action Model for Affordable and Efficient Robotics. [[Paper]](https://arxiv.org/abs/2506.01844) [[Code]](https://github.com/huggingface/lerobot) [[Project]](https://huggingface.co/blog/smolvla)

### Tutorials
- **Step-by-Step Diffusion** (2024): Step-by-Step Diffusion: An Elementary Tutorial. [[Paper]](https://arxiv.org/abs/2406.08929)
- **Flow Matching Guide** (2024): Flow Matching Guide and Code. [[Paper]](https://arxiv.org/abs/2412.06264) [[Code]](https://github.com/facebookresearch/flow_matching)
- **Robot Learning Tutorial** (2025): Robot Learning: A Tutorial. [[Paper]](https://arxiv.org/abs/2510.12403) [[Code]](https://github.com/fracapuano/robot-learning-tutorial) [[Project]](https://huggingface.co/spaces/lerobot/robot-learning-tutorial)

## Libraries
- [**Isaac Lab**](https://github.com/isaac-sim/IsaacLab) by NVIDIA: A unified robot learning framework built on Isaac Sim, with multi-physics and renderer support. [[How-to Guides]](https://isaac-sim.github.io/IsaacLab/develop/source/how-to/index.html)
- [**LeRobot**](https://github.com/huggingface/lerobot) by Hugging Face: An end-to-end robot learning library in PyTorch, with datasets, policies such as ACT, Diffusion Policy, π0, and SmolVLA, and support for low-cost robots like the SO-100 and Koch arms. [[Paper]](https://arxiv.org/abs/2602.22818) [[Docs]](https://huggingface.co/docs/lerobot)
- [**open-pi-zero**](https://github.com/allenzren/open-pi-zero) by [Allen Ren](https://github.com/allenzren): An unofficial re-implementation of π0 based on the paper, pairing a pre-trained PaliGemma VLM with a separate action expert trained with flow matching.
- [**Isaac Sim**](https://github.com/isaac-sim/IsaacSim) by NVIDIA: An open-source robotics simulator on NVIDIA Omniverse for importing robots and scenes, simulating physics and sensors, generating synthetic data, and testing robot stacks with ROS 2. [[Docs]](https://docs.isaacsim.omniverse.nvidia.com/6.2.0/index.html)
- [**RLinf**](https://github.com/RLinf/RLinf): Reinforcement learning infrastructure for embodied and agentic AI, including large-scale RL training of VLA models. [[Paper]](https://arxiv.org/abs/2509.15965) [[RLinf-VLA Paper]](https://arxiv.org/abs/2510.06710) [[Docs]](https://rlinf.readthedocs.io/en/latest/)

## Learning Resources
- [**Modern Robotics: Mechanics, Planning, and Control**](https://hades.mech.northwestern.edu/index.php/Modern_Robotics) by Kevin M. Lynch and Frank C. Park: A textbook on the fundamentals of robot kinematics, dynamics, motion planning, and control. [[PDF]](https://hades.mech.northwestern.edu/images/7/7f/MR.pdf) [[Code]](https://github.com/NxRLab/ModernRobotics)
- [**Spinning Up in Deep RL**](https://spinningup.openai.com/en/latest/) by OpenAI: An educational resource for deep reinforcement learning, with an introduction to key RL concepts, a curated list of key papers, exercises, and clean implementations of VPG, TRPO, PPO, DDPG, TD3, and SAC. [[Code]](https://github.com/openai/spinningup)
- [**Train an SO-101 Robot From Sim-to-Real With NVIDIA Isaac**](https://docs.nvidia.com/learning/physical-ai/sim-to-real-so-101/latest/01-overview.html) by NVIDIA: A learning path that trains a pick-and-place policy for the SO-101 arm with teleoperation data in simulation, then deploys it to the real robot.
- [**Isaac Lab Tutorial: SO-101 Vial Placement**](https://github.com/isaac-sim/IsaacLabTutorial) by NVIDIA: An Isaac Lab project that trains an SO-101 arm to place a vial upright in a rack, first learning a state policy with PPO and then distilling it into a wrist-camera policy that runs on the real robot. [[Course]](https://docs.nvidia.com/learning/physical-ai/getting-started-with-isaac-lab/latest/index.html)
- [**Learning Physical AI: A Sim-to-Real VLA Pipeline with Seeed reBot Arm and NVIDIA Isaac**](https://www.seeedstudio.com/sim-to-real-with-seeed-rebot-and-nvidia-isaac) by Seeed Studio: A sim-to-real VLA pipeline for the reBot Arm B601-RS, covering Cosmos Transfer data augmentation and Isaac GR00T N1.7 deployment with TensorRT on Jetson AGX Thor and Orin.

## YouTube
- [**VLA policies in robotics**](https://www.youtube.com/playlist?list=PLaqgu2SjelC6yZprhmbkLZUGXw3njRxME) by [Ilia](https://www.youtube.com/@ilialarchenko): A video series on Vision-Language-Action policies, covering VLA basics, π0, π0.5, and GR00T, plus a BEHAVIOR Challenge 1st-place solution walkthrough.
- [**LeHome Challenge at ICRA 2026**](https://www.youtube.com/playlist?list=PLLwBN_w7MtPk) by [Ilia](https://www.youtube.com/@ilialarchenko): The author's laundry-folding solution for the challenge, built with VLAs, reinforcement learning, sim2real, and DAgger-style human-in-the-loop data collection.
- [**RoboPapers**](https://www.youtube.com/@RoboPapers) by Chris Paxton and Michael Cho: Weekly conversations with the authors of robotics AI papers.

## Article
- [**Behavioral cloning mystery**](https://seohong.me/blog/behavioral-cloning-mystery/) by [Seohong Park](https://seohong.me/): Reproduces puzzling behavioral cloning phenomena seen with real robot data in a controlled simulated benchmark, and discusses their potential causes and implications.
- [**How robot arms are controlled**](https://x.com/ja_rothschild/status/2100633491432239411) by [Jacob H. Rothschild](https://x.com/ja_rothschild): How a robot arm such as the SO-100 is controlled, explained for ML practitioners new to robot learning.
- [**How ACT works**](https://x.com/ja_rothschild/status/2102818197393289678) by [Jacob H. Rothschild](https://x.com/ja_rothschild): Why and how ACT predicts a chunk of future actions instead of only the next one.
- [**How diffusion policies work**](https://x.com/ja_rothschild/status/2105680794480169137) by [Jacob H. Rothschild](https://x.com/ja_rothschild): Diffusion and flow matching built up from the VAE, as used by Diffusion Policy, GR00T, and most π models.
