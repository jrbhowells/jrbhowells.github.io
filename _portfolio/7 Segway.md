---
popup-id: "segway-popup"
tile-id: "segway"

tile-sub: "Electronics: Signals, Systems and Control"
tile-head: "Self-Balancing Mini Segway"

hero: "img/portfolio/segway/segway-tile.png"
---

<popup-box>
    <div>
        <div class="back">< Back</div>
        <h2>Self-Balancing Segway Project</h2>
    </div>
    <img src="img/portfolio/segway/segway-main.png" class="popup-main-img">
    <h2>Skills Developed</h2>
    <div class="pill">Coding: MicroPython</div><div class="pill">Problem Solving</div><div class="pill">Electronics: Feedback and Control</div>
    <h2>About the Project</h2>
    <p>Part of a module on systems and control, I used MicroPython to program a self-balancing segway using a PID controller. It had various modes, and could even dance to music.</p>
    <p>The Segway used Dr. Peter Cheung's <a href="http://www.ee.ic.ac.uk/pcheung/teaching/DE2_EE/Pybench%20User's%20Guide.pdf">PyBench board</a>, which includes an IMU and motor drivers among other things, with two wheels and a 9V battery.</p>
    <p>I used a PID controller, with the current angle of the segway as its input, to achieve self-balancing. The 'P' - proportional - term simply allows the segway to react when it's angle relative to vertical is not 0, while the I - integral - term removes any steady-state error that would cause the segway to drift sideways. The D - differential - term allows the segway to react to a rate of change of angle rather than simply to the angle being displaced. These together make for a fast and steady response to any change of angle and keep the segway upright for extended periods of time.</p>
    <br>
</popup-box>

