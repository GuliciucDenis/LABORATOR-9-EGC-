# LABORATOR-9-EGC-

1.Diferențele între iluminarea în lumea reală și în OpenGL:

În lumea reală, iluminarea este un proces complex, influențat de surse multiple, materiale și fenomene optice. OpenGL utilizează modele de iluminare simplificate, cum ar fi modelul Phong, care se concentrează pe sursele de lumină, fără a reproduce toate detaliile fizice complexe.

2.Sursele de lumină în OpenGL cu OpenTK:

Implementarea OpenGL cu OpenTK suportă un număr variabil de surse de lumină, limitat de specificațiile hardware și setările OpenGL ale dispozitivului. În general, OpenGL 4.x permite cel puțin 8 surse de lumină direcțională și punctuală.

3.Iluminarea de material în OpenGL:

Iluminarea de material în OpenGL include componentele ambientală, difuză și speculară. Ambientul reprezintă lumina ambientală constantă, difuzul reflectă iluminarea bazată pe unghiul dintre sursa de lumină și normala la suprafața obiectului, iar specularul gestionează reflectarea de la suprafețele lucioase.
Iluminarea de material este crucială în calcularea culorii pixelilor la randare.

4.Impactul sursei de lumină secundare comparativ cu o singură sursă:

Adăugarea unei surse de lumină secundare îmbunătățește realismul, creând umbre și evidențiind mai bine detaliile.
Cu o singură sursă de lumină, obiectele pot părea mai plate, în timp ce adăugarea sursei secundare contribuie la definirea umbrelor, oferind o percepție mai realistă a adâncimii și reliefurilor în scenă.
