---
popup-id: "fea-popup"
tile-id: "fea"

tile-sub: "Finite Element Analysis"
tile-head: "Tandem Bicycle Frame"

hero: "img/portfolio/fea/fea-tile.png"
---

<popup-box>
    <div>
        <img src="img/portfolio/fea/fea-header.png" style="margin-top: -30px; margin-bottom: 0;">
        <div class="back">< Back</div>
        <h2>Design of a Tandem Bicycle Frame using Finite Element Methods</h2>
    </div>
    <h2>Skills Developed</h2>
    <div class="pill">SolidWorks Simulation</div><div class="pill">Technical Analysis</div><div class="pill">Report Writing</div><div class="pill">CAD & Rendering</div>
    <h2>About the Project</h2>
    <p>I designed a tandem bike frame and analysed it with finite element methods, before making a second iteration, aiming to decrease frame mass and improve fundamental frequency.
    <h3>Mesh Refinement</h3>
    <img src="img/portfolio/fea/fea-refined-mesh.png" style="width: 25%;">
    <p>I decreased mesh size incrementally until this made only negligible differences to the results of a static simulation. I then used local mesh refinement to reduce stress concentrators in key areas where the uniform mesh was under-performing (above, mesh is refined where tubes join).</p>
    <h3>Study Parameters</h3>
    <img src="img/portfolio/fea/fea-loading.png" style="width: 25%;">
    <p>I added a 150kg mass to both seat posts (for the cyclists, including a factor of safety). The front fork was fixed (no degrees of freedom) and rear axle was hinged (rotationally free, translationally fixed), and I used oscillating 750 N remote loads 100 mm out and 200 mm forward from the crank cases to simulate pedalling.</p>
    <h3>First Iteration Results</h3>
    <img src="img/portfolio/fea/fea-frequency.png" style="width: 50%;">
    <p>I found that the fundamental frequency of the first iteration, at over 50 Hz, was well above the 30 Hz required by the project brief, and that the frame did not suffer from fatigue. For the second iteration, I removed the rear down tube from the design and made the tubes thicker in diameter, with the same wall thickness.</p>
    <h3>Second Iteration</h3>
    <img src="img/portfolio/fea/fea-frequency-2.png" style="width: 50%;">
    <p>Mass of the second-iteration frame decreased by around 1%, and fundamental frequency was successfully increased by 12.3%. The fatigue life of this frame, when made out of aluminium and under the above loading conditions, was found to be 1.26 million cycles.</p>
    <a class="button" href="doc/FEA_Bike.pdf">Full Report</a>
</popup-box>
