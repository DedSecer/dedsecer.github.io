<style>.project-gallery { display: flex; overflow-x: auto; gap: 0.5rem; margin-bottom: 1rem; scroll-snap-type: x mandatory; padding-bottom: 0.5rem; scrollbar-width: thin; scrollbar-color: var(--color-accent) transparent; } .project-gallery::-webkit-scrollbar { height: 6px; } .project-gallery::-webkit-scrollbar-track { background: transparent; } .project-gallery::-webkit-scrollbar-thumb { background-color: var(--color-accent); border-radius: 10px; } .project-gallery img { flex: 0 0 100%; width: 100%; border-radius: 0.25rem; aspect-ratio: 16/9; object-fit: cover; object-position: center; scroll-snap-align: center; } .project-grid-images { display: grid; grid-template-columns: 1fr 1fr; gap: 0.5rem; margin-bottom: 1rem; } .project-grid-images img { width: 100%; border-radius: 0.25rem; aspect-ratio: 16/9; object-fit: cover; object-position: center; }</style>
<h1 class="title">Project Experience</h1>
<div class="project-grid">
    <div class="project-card">
        <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 0.5rem; flex-wrap: wrap;">
            <h3 style="margin: 0; margin-right: 1rem;">Humanoid Whole-Body Control</h3>
            <span style="font-size: 0.875rem; color: var(--color-accent); font-family: 'JetBrains Mono', monospace;">2026 – Present</span>
        </div>
        <div class="project-gallery">
            <img src="assets/project/Humanoid-Whole-Body-Control/cover.png" alt="Humanoid 1" loading="lazy"  style="object-fit: contain;">
        </div>
        <p>Built a reinforcement learning pipeline for the Tienkung humanoid robot in Isaac Sim, achieving human-stylized locomotion via <strong>Adversarial Motion Priors (AMP)</strong>. Validated through Sim2Sim transfer before deploying to the physical robot via Sim2Real. Developed a <strong>Whole-Body Control (WBC)</strong> system that extracts skeletal poses from human motion videos, retargets joint trajectories onto the robot's kinematic structure, and trains RL policies to track full-body movements.</p>
        <div class="project-links">
        </div>
    </div>
    <div class="project-card">
        <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 0.5rem; flex-wrap: wrap;">
            <h3 style="margin: 0; margin-right: 1rem;">STEM Education Robot Kit</h3>
            <span style="font-size: 0.875rem; color: var(--color-accent); font-family: 'JetBrains Mono', monospace;">2025 – 2026</span>
        </div>
        <div class="project-gallery">
            <img src="assets/project/education-robot/car.png" alt="STEM Education Robot Kit 1" loading="lazy">
            <img src="assets/project/education-robot/car2.png" alt="STEM Education Robot Kit 2" loading="lazy">
        </div>
        <p>Led software development for a STEM education robot at a startup, taking ownership of the full software stack from low-level motor control to high-level task orchestration. Implemented <strong>motor drive and closed-loop control</strong> on ESP32, encapsulating chassis kinematics and servo/stepper motor libraries for modular control. On the perception and navigation side, leveraged <strong>RDK X3 with AprilTag</strong> for precise indoor localization and autonomous navigation, and developed <strong>AprilTag-based recognition and alignment</strong> for automated pick-and-place docking. Unified all subsystems into a <strong>state machine</strong> that robustly orchestrates the full mission workflow. The project shipped to mass production, delivering a complete and commercially viable product.</p>
        <div class="project-links">
        </div>
    </div>
    <div class="project-card">
        <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 0.5rem; flex-wrap: wrap;">
            <h3 style="margin: 0; margin-right: 1rem;">HKUST(GZ) Go-Kart Creation Camp</h3>
            <span style="font-size: 0.875rem; color: var(--color-accent); font-family: 'JetBrains Mono', monospace;">Feb 2026</span>
        </div>
        <div class="project-gallery">
            <img src="assets/project/gokart/gokart1.jpeg" alt="Go-Kart 1" loading="lazy">
            <img src="assets/project/gokart/gokart2.jpg" alt="Go-Kart 2" loading="lazy">
            <img src="assets/project/gokart/gokart3.jpg" alt="Go-Kart 3" loading="lazy">
            <img src="assets/project/gokart/gokart4.jpg" alt="Go-Kart 4" loading="lazy">
        </div>
        <p>Served as a teaching assistant at The Hong Kong University of Science and Technology (Guangzhou) Go-Kart Creation Camp, instructing secondary-school students on <strong>motor drive circuits, microcontroller fundamentals, and vehicle mechanical design</strong>. Guided students through MCU-based motor control, mechanical assembly, hardware debugging, and full-system integration — bridging theory to a complete working go-kart build.</p>
        <div class="project-links">
        </div>
    </div>
    <div class="project-card">
        <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 0.5rem; flex-wrap: wrap;">
            <h3 style="margin: 0; margin-right: 1rem;">Cathay Hackathon — Edge AI Companion</h3>
            <span style="font-size: 0.875rem; color: var(--color-accent); font-family: 'JetBrains Mono', monospace;">Nov 2025</span>
        </div>
        <div class="project-gallery">
            <img src="assets/project/cathay/cathay5.png" alt="Cathay 5" loading="lazy">
            <img src="assets/project/cathay/cathay.png" alt="Cathay 1" loading="lazy">
            <img src="assets/project/cathay/cathay2.png" alt="Cathay 2" loading="lazy">
            <img src="assets/project/cathay/cathay3.png" alt="Cathay 3" loading="lazy">
            <img src="assets/project/cathay/cathay4.png" alt="Cathay 4" loading="lazy">
        </div>
        <p>Designed the product and system architecture for a child-safety companion device, deploying an <strong>offline LLM on RDK X5 edge hardware</strong> integrated with IMU and biosensors for real-time emotion recognition. Engineered the end-to-end data flow connecting the edge device, Cloud Agent, Parent App, and Crew Dashboard, ensuring safety transparency and seamless communication. Applied <strong>GenAI and cloud-computing</strong> methodologies from AWS, Google Cloud, and Microsoft masterclasses to strengthen solution feasibility and scalability.</p>
        <div class="project-links">
        </div>
    </div>
    <div class="project-card">
        <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 0.5rem; flex-wrap: wrap;">
            <h3 style="margin: 0; margin-right: 1rem;">RoboMaster Engineering Robot</h3>
            <span style="font-size: 0.875rem; color: var(--color-accent); font-family: 'JetBrains Mono', monospace;">2024 – 2025</span>
        </div>
        <div class="project-gallery">
            <img src="assets/project/RoboMaster/1.png" alt="RoboMaster 1" loading="lazy" style="object-fit: contain;">
            <img src="assets/project/RoboMaster/2.jpg" alt="RoboMaster 2" loading="lazy" style="object-fit: contain;">
            <img src="assets/project/RoboMaster/4.jpg" alt="RoboMaster 4" loading="lazy">
        </div>
        <p>Contributed to the university RoboMaster team's engineering robot. Selected and assembled actuators to build a custom manipulator arm, then implemented <strong>inverse kinematics</strong> via the MoveIt framework in ROS for end-effector positioning. Designed a custom controller enabling intuitive <strong>teleoperation</strong> of the arm during competition tasks.</p>
        <div class="project-links">
        </div>
    </div>
    <div class="project-card">
        <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 0.5rem; flex-wrap: wrap;">
            <h3 style="margin: 0; margin-right: 1rem;">ICRA 2024 Sim2Real Challenge</h3>
            <span style="font-size: 0.875rem; color: var(--color-accent); font-family: 'JetBrains Mono', monospace;">2024</span>
        </div>
        <div class="project-gallery">
            <img src="assets/project/ICRA-Sim2Real-Challenge/5.png" alt="ICRA Sim2Real Challenge 5" loading="lazy" style="object-fit: contain;">
            <img src="assets/project/ICRA-Sim2Real-Challenge/1.png" alt="ICRA Sim2Real Challenge 1" loading="lazy">
            <img src="assets/project/ICRA-Sim2Real-Challenge/4.png" alt="ICRA Sim2Real Challenge 4" loading="lazy" style="object-fit: contain;">
            <img src="assets/project/ICRA-Sim2Real-Challenge/2.png" alt="ICRA Sim2Real Challenge 2" loading="lazy">
            <img src="assets/project/ICRA-Sim2Real-Challenge/3.jpg" alt="ICRA Sim2Real Challenge 3" loading="lazy">
        </div>
        <p>Developed an integrated perception-and-control pipeline for a mobile manipulator in simulation, combining <strong>visual perception</strong> with coordinated <strong>chassis and arm control</strong> to autonomously organize a cabinet and desktop environment. After validating task completion in simulation, transferred the full algorithm stack to a physical robot, addressing the Sim2Real gap to achieve reliable real-world execution.</p>
        <div class="project-links">
        </div>
    </div>
    <div class="project-card">
        <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 0.5rem; flex-wrap: wrap;">
            <h3 style="margin: 0; margin-right: 1rem;">Quadruped SLAM Navigation</h3>
            <span style="font-size: 0.875rem; color: var(--color-accent); font-family: 'JetBrains Mono', monospace;">2023 – 2024</span>
        </div>
        <div class="project-gallery">
            <img src="assets/project/SLAM/deep1.jpg" alt="SLAM 1" loading="lazy">
            <img src="assets/project/SLAM/dog.jpg" alt="SLAM 3" loading="lazy" style="object-fit: contain;">
            <img src="assets/project/SLAM/slam.jpg" alt="SLAM 4" loading="lazy">
        </div>
        <p>Implemented a <strong>LiDAR-based SLAM</strong> system for simultaneous mapping and autonomous navigation, and deployed the full pipeline on a quadruped robot. Achieved robust mapping and path planning performance across both indoor and outdoor environments.</p>
        <div class="project-links">
        </div>
    </div>


</div>
