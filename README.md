# SkyShield: Protecting Earth and Satellites from Space Hazards
**Space Apps Challenge 2024**

The project is a JavaScript Web app of a physically based virtual interactive orrery. The app can display the main planets along with 5 dwarf planets (Ceres, Eris, Pluto, Haumea, and Makemake), and the population of near Earth objects (NEOs) on the ESA risk list. A few parent bodies of meteoroid streams are also viewable, along with some orbits of detected meteors (associated with their parent body if it is known). A general area of the sporadic meteoroid complex's distribution is additionally viewable as a decaying gradient centered on the Sun. All of these object groups are toggleable to be either visible or not. The orbits of the objects are computed from their physical orbital elements, along with their specific epoch, allowing their true locations to be shown at the correct time. The flow of time can be set to real time, speed up, or reversed, to better see the motion of the objects. The objects are selectable and display an information window when clicked, providing data such the object name, its orbital parameters, asteroid class, and more. Since this project has a focus on the natural objects in space which can pose a risk to either Earth and/or satellites, the visualized meteoroid streams are handled differently. The meteoroid streams with known parent bodies have the parent body orbits always visible (except if disabled), while the orbits of the associated meteors (or meteors with no known parent bodies) have their orbits appear only when their meteoroid stream is active (close to earth).

 **There are :**
- 8 planets
- 5 dwarf planets
- 1669 NEOs
- 34 showers with 107 streams
- The sporadic complex

To facilitate sorting through the 1669 NEOs on the risk list, a custom filtering system was included to only display a subset of the total NEOs. They can be filtered by bounding a minimum and maximum value of: semi-major axis, eccentricity, object diameter, and the impact risk (Palermo rating). 

# IDEAS implemented during the Space Apps Challenge 2024

 **TO DO**
- [x] CSV Planets ephemeris J2000
- [x] CSV Sporadics meteor showers and parent bodies J2000
- [x] CSV Risk list asteroids J2000
- [x] CSV to json file Python
- [x] Orbit and body
- [x] Matrix rotation function
- [x] Toggle Satelite/Earth and slider JD and number of shown NEOs
- [x] Python to Javascript conversion to boot the page
- [x] make it load faster the orbit
- [x] Textures for planets and Sun
- [x] Add key for centering the camera to the Sun
- [x] Add key for resetting the camera entirely
- [x] Add key to center camera on currently selected object
- [x] True anomaly fix
- [x] Add planet labels
- [x] Make info panel for planets work
- [x] Make time controls work
- [x] Make filter controls work
- [x] Make planets rotate
- [x] UI Filters
- [x] Keyboard controls
- [ ] Overlay showing keyboard controls
- [x] DEMO ppt submit by 6pm with title explain what the screen capture is showing

**if time allows**
- [x] Skybox milkyway
- [ ] Moons
- [ ] Texture planet atmosphere
- [x] Texture and halo Sun
