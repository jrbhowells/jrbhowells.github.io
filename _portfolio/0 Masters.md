---
popup-id: "masters-popup"
tile-id: "masters"

tile-sub: "Master's Project"
tile-head: "Soft Robotic Arm and Control"

hero: "img/portfolio/masters/Hero.png"
---

<popup-box>
    <div class="popup-navbar">
        <h2>Master's Project: Soft Robotic Arm and Control System</h2>
    </div>
    <img src="img/portfolio/masters/X-1.png" class="popup-main-img">
    <h2>Skills Developed</h2>
    <div class="pill">CAD</div><div class="pill">Mechanical Design</div><div class="pill">Pneumatic Design</div><div class="pill">Prototyping</div><div class="pill">3D Printing</div><div class="pill">Electronics Design</div>
    <h2>About the Project</h2>
    <p>Soft robotics is a very promising field of research. Conventional robotics produces ever more capable robots, so the switch to researching less-developed soft alternatives can seem counterintuitive – however, soft robots have the capability to transform robotics in certain applications. Conventional robots can, in some situations, pose a danger to their operators by their noncompliant nature, and there are some applications for which conventional robots are not well suited. For example, navigating in confined spaces or unstructured environments - such as the inside of a human body (for surgery) or rubble in the aftermath of natural disasters (for search and rescue).</p>
    <p>This project aimed to to develop and evaluate a minimalistic actuation strategy for multi-segment pneumatic continuum robots, and to design and build a robot with which to test this actuation system.</p>
    <p>The full report can be found on the project website, below.</p>
    <h3>Background</h3>
    A pneumatic soft continuum robot is made up of multiple segments, each of wehich are individually-controllable. They work by having multiple hollow chambers inside them which are reingorced radially: if we pressurise these chambers, they must expand axially (i.e. get longer). By positioning several chambers around a segment, we can bend the segment using the air pressure of the chambers alone.
    <h3>1. Hardware & Electronics</h3>
    <img src="img/portfolio/masters/PressSys.png" style="width:50%;">
    <p>The actuation system consists of the hardware and software needed to supply a programmable pressure individually to every chamber in the soft continuum robot. The one I developed for this project is the first stystem optimised for pneumatic soft continuum robots that uses fewer pumps than chambers: this greatly reduces the cost of the system (95% reduction), but adds to the complexity of the control algorithm.</p>
    <h4>System</h4>
    <p>The system uses three low-cost peristaltic pumps, connected to five solenoid valves each, to control the air pressure in the robot's chambers:</p>
    <img src="img/portfolio/masters/SysDia Inflate.png" style="width:35%;">
    <img src="img/portfolio/masters/SysDia Deflate.png" style="width:35%;">
    <h4>Algorithm Design</h4>
    <img src="img/portfolio/masters/FlowChart.png" style="width:35%;">
    <p>The control algorithm I developed uses feedback to produce the required pressure. It continually checks the current pressure of the segments, and uses several inflation and deflation strategies to overcome the limitations of the hardware used in order to get the pressure to the desired value.</p>
    <p>It would have been possible to circumvent the need for a lot of the stages in the above flowchart by using higher-quality hardware, but this would go against the project aim of costing soft robotics down - and given that the limitations could be overcome in software it was no great loss.</p>
    <h3>2. Segment Casting & Process Innovation</h3>
    <p>An area of soft robotics that needs considerable innovation is the semgent design, because the literature tends to focus on better control systems or applications for robots - not the segments themselves. For this project, I developed a new process for casting segments (the segment design itself represents an evolution on the common STIFF-FLOP design). The process cut manufacture time per segment from around a week to around one day, inclusing silicone curing times. The full casting process is described on the project's website (see below).</p>
    <img src="img/portfolio/masters/MadeSeg.png" style="width:80%;">
    <p>A full segment (shown in the above image) has six chambers inside it, which are connected in pairs to create three separate zones. Pressurising each zone can bend the robot in any direction. This gives the segment very good dexterity in navigating obstacles (see below), even at relatively low pressures (around 0.8 bar is sufficient in most applications).</p>
    <img src="img/portfolio/masters/ObstacleWrap.png" style="width:35%;">
    <br><br>
    <p>The full report, as well as more information about parts of the system, can be found on the project website:</p>
    <a class="button" href="https://3-pscr.github.io/">Project Website</a>    
</popup-box>
