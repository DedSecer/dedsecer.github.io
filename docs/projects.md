<style>.project-gallery { display: flex; overflow-x: auto; gap: 0.5rem; margin-bottom: 1rem; scroll-snap-type: x mandatory; padding-bottom: 0.5rem; scrollbar-width: thin; scrollbar-color: var(--color-accent) transparent; } .project-gallery::-webkit-scrollbar { height: 6px; } .project-gallery::-webkit-scrollbar-track { background: transparent; } .project-gallery::-webkit-scrollbar-thumb { background-color: var(--color-accent); border-radius: 10px; } .project-gallery img { flex: 0 0 100%; width: 100%; border-radius: 0.25rem; aspect-ratio: 16/9; object-fit: cover; object-position: center; scroll-snap-align: center; } .project-grid-images { display: grid; grid-template-columns: 1fr 1fr; gap: 0.5rem; margin-bottom: 1rem; } .project-grid-images img { width: 100%; border-radius: 0.25rem; aspect-ratio: 16/9; object-fit: cover; object-position: center; }</style>
<h1 class="title">Project Experience</h1>
<div class="project-grid">
    <div class="project-card">
        <!-- 横向滚动相册展示多图 -->
        <div class="project-gallery">
            <img src="assets/AgentBreederDiagramJPG.jpg" alt="Agent Breeder 1">
            <img src="assets/screenshot.png" alt="Agent Breeder 2">
            <img src="assets/transformerlens_preview-1.png" alt="Agent Breeder 3">
        </div>
        <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 0.5rem; flex-wrap: wrap;">
            <h3 style="margin: 0; margin-right: 1rem;">Agent Breeder</h3>
            <span style="font-size: 0.875rem; color: var(--color-accent); font-family: 'JetBrains Mono', monospace;">Jan 2025 - Sep 2025</span>
        </div>
        <p>An automated pipeline for evolving multi-agent systems. Explores the dynamics of cooperation and competition in LLM-based autonomous agents through evolutionary algorithms and structured environments.</p>
        <div class="project-links">
            <a href="#">Paper</a>
            <a href="#">GitHub</a>
        </div>
    </div>
    <div class="project-card">
        <!-- 静态网格展示多图 -->
        <div class="project-grid-images">
            <img src="assets/infusion_big_figure.jpg" alt="Project Infusion 1">
            <img src="assets/mapping_faithful.jpg" alt="Project Infusion 2">
        </div>
        <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 0.5rem; flex-wrap: wrap;">
            <h3 style="margin: 0; margin-right: 1rem;">Project Infusion</h3>
            <span style="font-size: 0.875rem; color: var(--color-accent); font-family: 'JetBrains Mono', monospace;">Oct 2025 - Present</span>
        </div>
        <p>A novel framework for infusing large language models with external knowledge graphs, enhancing reasoning capabilities, factual accuracy, and reducing hallucinations in specialized domains.</p>
        <div class="project-links">
            <a href="#">Code</a>
            <a href="#">Demo</a>
        </div>
    </div>
    <div class="project-card">
        <img src="assets/stream_jpg.jpg" alt="Streaming Architecture" style="width: 100%; border-radius: 0.25rem; margin-bottom: 1rem; aspect-ratio: 16/9; object-fit: cover; object-position: center;">
        <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 0.5rem; flex-wrap: wrap;">
            <h3 style="margin: 0; margin-right: 1rem;">Stream Architecture</h3>
            <span style="font-size: 0.875rem; color: var(--color-accent); font-family: 'JetBrains Mono', monospace;">May 2024 - Dec 2024</span>
        </div>
        <p>A high-performance real-time data processing engine built for modern web applications. Handles complex event streams with minimal latency and high throughput for robotics and control systems.</p>
        <div class="project-links">
            <a href="#">Architecture Details</a>
        </div>
    </div>
    <div class="project-card">
        <img src="assets/mapping_faithful.jpg" alt="Faithful Mapping" style="width: 100%; border-radius: 0.25rem; margin-bottom: 1rem; aspect-ratio: 16/9; object-fit: cover; object-position: center;">
        <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 0.5rem; flex-wrap: wrap;">
            <h3 style="margin: 0; margin-right: 1rem;">Faithful Mapping</h3>
            <span style="font-size: 0.875rem; color: var(--color-accent); font-family: 'JetBrains Mono', monospace;">Feb 2024 - Apr 2024</span>
        </div>
        <p>Research on faithful concept mapping within deep neural networks to improve interpretability, feature extraction transparency, and trust in complex AI perception systems.</p>
        <div class="project-links">
            <a href="#">Research Paper</a>
        </div>
    </div>
</div>
