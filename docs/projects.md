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
        <p>
        Built a reinforcement learning pipeline for humanoid whole-body control in Isaac Sim, focusing on <strong>motion imitation</strong> and <strong>Sim2Real transfer</strong>. Developed a <strong>Whole-Body Control (WBC)</strong> framework that extracts human skeletal motion from videos, retargets trajectories to the humanoid robot, and trains RL policies to track full-body movements. Trained humanoid locomotion policies with <strong>Adversarial Motion Priors (AMP)</strong>, enabling natural and human-like behaviors, and deployed the controller from simulation to the physical robot after Sim2Sim validation.
        </p>
        <div class="project-links">
        </div>
    </div>
    <div class="project-card">
        <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 0.5rem; flex-wrap: wrap;">
            <h3 style="margin: 0; margin-right: 1rem;">Morphology-Aware Quadrupedal Locomotion</h3>
            <span style="font-size: 0.875rem; color: var(--color-accent); font-family: 'JetBrains Mono', monospace;">May 2026</span>
        </div>
        <div class="project-gallery">
            <img src="assets/project/MAQL/1.jpg" alt="MAQL 1" loading="lazy">
            <img src="assets/project/MAQL/2.png" alt="MAQL 2" loading="lazy" style="object-fit: contain;">
        </div>
        <p>
        Collaborated with senior researchers at <strong>HKUST(GZ)</strong> on reinforcement learning-based quadruped locomotion under embodiment uncertainty. The project focused on morphology adaptation through per-limb randomization, target-height conditioning, proprioceptive leg-length inference, and robustness evaluation across A1 simulations and Unitree Go2.
        </p>
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
        <p>
        Led software development for a STEM education robot product, covering <strong>embedded control</strong>, perception, and task orchestration. Implemented <strong>closed-loop motor control</strong> on ESP32 and developed modular chassis and actuator control libraries. Built an <strong>AprilTag-based localization and autonomous docking</strong> system on RDK X3, and integrated all subsystems through a robust <strong>state-machine architecture</strong>. The project was successfully shipped to <strong>mass production</strong> as a commercially deployed product.
        </p>
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
        <p>
        Served as a teaching assistant at the HKUST(GZ) Go-Kart Creation Camp, mentoring students in <strong>motor control</strong>, embedded systems, and vehicle mechanical design. Guided teams through hardware assembly, MCU-based motor control, debugging, and full-system integration to build fully functional electric go-karts, bridging engineering theory with hands-on robotics practice.
        </p>
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
        <p>
        Designed the system architecture for an <strong>edge-AI companion device</strong> on RDK X5 hardware, integrating online language models with IMU and biosensor data for real-time interaction and emotion recognition. Built the end-to-end communication pipeline connecting edge devices, cloud services, parent applications, and monitoring dashboards, enabling reliable and low-latency multi-device coordination.
        </p>
        <div class="project-links">
            <a href="https://github.com/DedSecer/Captaion-Milo-web" target="_blank" rel="noopener">Code(UI)</a>
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
        <p>
        Developed a robotic manipulator for the university RoboMaster engineering robot, implementing <strong>inverse kinematics</strong> and end-effector control through ROS and the <strong>MoveIt</strong> framework. Designed a custom <strong>teleoperation controller</strong> for intuitive manipulation during competition tasks, improving operational efficiency and control stability.
        </p>
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
        <p>
        Developed an integrated <strong>perception-and-control pipeline</strong> for a mobile manipulator, combining visual perception with coordinated chassis and robotic arm control to perform autonomous object organization tasks in simulation. Transferred the full algorithm stack from simulation to a physical robot, achieving reliable <strong>Sim2Real deployment</strong> in real-world environments.
        </p>
        <div class="project-links">
            <a href="https://github.com/sztu-sim2real/ICRA2024-Sim2Real-AXS" target="_blank" rel="noopener">Code</a>
            <a href="http://www.sim2real.net/track/track?nav=AXS2024&type=nav&t=1778836433281" target="_blank" rel="noopener">Website</a>
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
        <p>
        Developed and deployed a <strong>LiDAR-based SLAM</strong> and autonomous navigation system on a quadruped robot, enabling real-time mapping, localization, and path planning across indoor and outdoor environments. Integrated the full navigation pipeline on the physical platform and achieved robust autonomous operation in complex scenes.
        </p>
        <div class="project-links">
            <a href="https://github.com/DedSecer/go1_navigation" target="_blank" rel="noopener">Code(g1)</a>
            <a href="https://github.com/DedSecer/coffee_nav" target="_blank" rel="noopener">Code(lite3)</a>
        </div>
    </div>


</div>
