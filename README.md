# tp2.3
Question1:
Quelle méthode de constructeur utilisez-vous pour créer une intention implicite de lancer une application de caméra?

  -> new Intent(String action)


Question2:
Lorsque vous créez un objet Intention implicite, lequel des énoncés suivants est vrai?

  ->Ajoutez une action d'intention ou une catégorie d'intention (ou les deux).


Question3:
Quelle action Intention utilisez-vous pour prendre une photo avec une application appareil photo?

  ->Intent takePicture = new Intent(MediaStore.ACTION_IMAGE_CAPTURE);
