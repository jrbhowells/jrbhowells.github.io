---
popup-id: "gizmo-popup"
tile-id: "gizmo"

tile-sub: "Gizmo: Physical Computing"
tile-head: "The Useless Box"

hero: "img/portfolio/gizmo/gizmo-tile.png"
---

<popup-box>
    <div>
        <div class="back">< Back</div>
        <h2>Physical Computing: The Useless Box</h2>
    </div>
    <img src="img/portfolio/gizmo/gizmo-main.png" class="popup-main-img">
    <h2>Skills Developed</h2>
    <div class="pill">CAD</div><div class="pill">Mechanical Design</div><div class="pill">Prototyping</div><div class="pill">Arduino</div><div class="pill">Electronics</div>
    <h2>About the Project</h2>
    <p>A its name suggests, the Useless Box is a box that does very little that is of use to anyone. The box can get progressively more ‘annoyed’ as the user turns the switch on - at first, it simply turns the switch back off but as it gets more exasperated about this not working, it starts to take more action - hiding the switch from the user, or even running away.</p>
    <p>The way the box reacts (how vigorously it turns the switch off) depends on how fast the user switches it on: the longer the user takes to turn the switch on, the ‘sneakier’ the box is about turning it off.</p>
    <img src="img/portfolio/gizmo/gizmo-mechs.png">
    <h3>Electronics</h3>
    <p>The whole box is controlled by an Arduino Uno, which takes inputs from the switch and ultrasonic distance sensor. These are then used to control one of four SG90 servos (switch off the switch, hide the switch, pop the eyes up, run away). All the servos are connected to a common power and ground rail, and their signal wires are routed to the arduino.</p>
    <h3>Modified Servo</h3>
    <img src="img/portfolio/gizmo/gizmo-servo.png" style="width: 75%;">
    <p>In order to use a regular SG90 servo to power the wheels, I modified it for continuous rotation by removing the potentiometer and replacing it with two 5 kΩ resistors. This means that the servo doesn’t know what angle it is at, and so continues rotating while any angle other than 90° is selected in the code.</p>
    <iframe style="width: 50vw; height: calc(50vw * 315/560)" src="https://www.youtube.com/embed/7Mt-p6ccgrQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    <br><br>
    <a class="button" href="doc/Gizmo_Poster.pdf">See Poster</a>
</popup-box>

