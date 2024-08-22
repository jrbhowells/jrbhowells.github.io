---
popup-id: "garmin-venio-popup"
tile-id: "garmin-venio"

tile-sub: "Industrial Design Engineering II"
tile-head: "Garmin* Venio: Navigation for Cyclists"

hero: "img/portfolio/ide2/venio-exploded.jpg"
---

<popup-box>
    <div>
        <img src="img/portfolio/ide2/venio-rider.png" style="margin-top: -30px; margin-bottom: 0;">
        <div class="back">< Back</div>
        <h2 style="background-color: rgba(0,0,0,0.3); box-shadow: 0 0 10px 10px rgba(0,0,0,0.3);">Garmin* Venio: Navigation for Urban Cyclists</h2>
        <p>*Garmin were not engaged in any consultancy or collaborative capacity in this project and the outcome is in no way endorsed by them. Any publicity is limited to personal and academic use.</p>
    </div>
    <h2>Skills Developed</h2>
    <div class="pill">CAD</div><div class="pill">Technical Drawing</div><div class="pill">Rendering: KeyShot</div><div class="pill">Prototyping</div><div class="pill">3D Printing</div><div class="pill">Electronics Design</div><div class="pill">DFMA</div><div class="pill">Coding</div><div class="pill">Industrial Design</div>
    <h2>About the Project</h2>
    <p>Garmin Venio is a tool to help new and inexperienced cyclists navigate the roads of a city, and features built-in GPS and haptic feedback to guide users. As a group, we developed all aspects of the product, including branding, packaging, compliance and labelling, as well as producing a fully working prototype and a set of technical drawings for production.</p>
    <p>Venio is designed not to take attention away from the road: vibration motors in the silicone neck band guide the wearer with vibration patterns. Users set a destination on an app, and the route is then uploaded to Venio and processed locally.</p>
    <h3>Electronics</h3>
    <img src="img/portfolio/ide2/venio-techdraw.png" style="width:50%;">
    <p>Venio uses an ESP32, a GPS module and two vibration motors, powered by a 500 mAh battery. While these exact components wouldn’t be used in a commercial product, components were selected based chiefly on price and availability: Venio is targeted at less-professional sportspeople (unlike other Garmin products) so a low price point was essential.</p>
    <img src="img/portfolio/ide2/venio-pseudocode.png" style="width:15%;">
    <p>The device is programmed in MicroPython: this pseudocode gives a brief explanation of what it does.</p>
    <h3>DFMA</h3>
    <p>Fitting the electronics into a small casing proved extremely difficult and took over a hundred iterations in CAD before I was happy with the result (in order to do this, I had to create accurate models of all the electronic components too). Final design and technical drawings fully specified all parts of the casing and product, and costing and injection moulding simulations were used to further refine the design.</p>
    <h3>Prototype Manufacture</h3>
    <p>Several versions of the casing were 3D printed to test electronics for fit. Once I was happy, I soldered all the electronic components and installed them. The custom magnetic clasp was also printed, and the silicone bands were made using cloth - we did not have access to silicone.</p>
    <iframe style="width: 50vw; height: calc(50vw * 315/560)" src="https://www.youtube.com/embed/F8R3wY_P6nI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    <br><br>
    <a class="button" href="doc/IDE_Venio.pdf">Full Documentation</a>    
</popup-box>
