# Portfolio 

I am a young graduate in space sciences who loves sharing sciences. Here are some samples of my volunteering projects.

## Science writing

I have published around 50 science communication posts on social media as a volunteer for an association (Astronomical Society of Liège). Thanks to my background in space sciences, I can ccurately explain complex aspects of our Universe. The topics are very diverse. Black hole processes, cosmology, history of science discoveries, extragalactic astrophysics, planetology, radio astrophysics, etc. Some of my posts are listed below with the links to their original publication on Instagram.

[An interactive game about tidal effects around a black hole.](https://www.instagram.com/p/CtXUSd1NTRk/?img_index=1)

[Third post about the theoretical pilars of the Big Bang.](https://www.instagram.com/p/CwLMLtFNDy-/?img_index=1)

## Black hole raytracer

I have created a simple black hole raytracer in Python. It highlights the gravitational lensing effect and the event horizon of a Schwarzschild black hole for an observer outside the black hole. The project can be summarized in three steps. First, we have to solve the light-like geodesic equation of General Relativity for a Schwarzschild black hole. Second, we have to consider the following situation to drastically reduce the computation time : the observer emits photons and if a photon hits a pixel of the background image, then this pixel is turned on. By processing recursively these two steps, I finally obtain such images.

![A stellar Schwarzschild black hole in space. The background image is the famous Hubble field.](https://github.com/ipfungi/Portfolio/blob/main/raytracer.png "A stellar Schwarzschild black hole in space. The background image is the famous Hubble field.")

This is the lensing effect and the event horizon of a Schwarzschild black hole. Note that this simulation does not take into account rotations of photons around the black hole. Here, we only see the image formed by direct photons (i.e. the rotation angle does not exceed pi). The event horizon is thus overestimated. The background image is the famous Hubble field. The python code has been created with numpy, matplotlib, and PIL (source code [here](https://github.com/ipfungi/Black-hole-raytracer)).  

## Inspiral

This project concerns the animation of gravitational radiation during a black-hole inspiral. This two-body system evacuates gravitational energy during its orbital motion. Each black hole gets closer to the other while the overall motion emits spherical gravitational waves. The radiation and the orbital frequency increase during the inspiral until the collision. The ringdown phase and the merger are not simulated since they require specific tools associated with numerical relativity. 

[My animation of a black-hole inspiral.](https://www.instagram.com/p/C1hLxmXN2Y1/)

This python simulation has been created with numpy and matplotlib (source code [here](https://github.com/ipfungi/binary-merger)). It is an OOP project. 


