# Activitat 4:

## Gestió d'usuaris:

Hi ha dos tipus d'usuaris, els admins amb permissos per gestionar Owncloud i els usuaris normals.

On fica resposta afegeix una captura de pantalla on es vegi que has fet l'acció que es demana.

**Aquesta part de la pràctica la feu amb un company/a, li creeu un usuari i li doneu el vostre nom de domini d'Owncloud.**

Per a que pugui accedir necessitarà:

- La MV amb owncloud ha d'estar en mode "adaptador pont".
- El fitxer /etc/hosts del company ha de tenir la IP de la MV i el nom de domini de la MV del company/a.


**4.1.-** Crea un usuari admin que es digui adminXYZ, on XYZ són les inicials del teu nom:

**RESPOSTA**

![](crearusuari.png)

**4.2.-** Inicia sessió com a l'usuari adminXYZ.

**RESPOSTA**

![](inicisessio.png)

**4.3.-** Crea un usuari XYZ on XYZ son les inicials del company/a i afegeix-lo al grup usuaris, aquest usuari tindrà una quota de 512 MB.

**RESPOSTA**

![](company.png)

**4.4.-** Podem crear fitxers d'una mida determinada a Linux amb la comanda:

```
truncate -s 10M file.txt
```

A l'exemple es crea un fitxer de 10MB.

Crea 6 fitxers de 100MB i pujal's a Owncloud un per un.

**RESPOSTA**

![](crearfitxers.png)

**4.5.-** Mostra el missatge d'error per haver superat la quota d'usuari.

**RESPOSTA**

![](error.png)

**4.6.-** Busca al teu perfil quin percentatge de quota estas utilitzant.

**RESPOSTA**

![](quota.png)

**4.7.-** Canvia la quota de l'usuari a 1GB i mostra tots els fitxers pujats.

**RESPOSTA**

![](1GB.png)

![](1GB(2).png)

**4.8.-** Crea un usuari anomenat usuari2XYZ i fical al grup usuaris.

**RESPOSTA**

![](usuari2.png)

**4.9.-** Comparteix un fitxer de usuariXYZ a usuari2XYZ i mostra com l'usuari2XYZ pot veure i descarregar el fitxer.

**RESPOSTA**

![](comprateixidescarregar.png)

**4.10.-** Esborra la carpeta Learn more about owncloud.

**RESPOSTA**

![](esborra.png)

**4.11.-** Recupera la carpeta Learn more about owncloud.

**RESPOSTA**

![](recupera.png)

**4.12.-** Com a usuariXYZ crea una carpeta nova anomenada shared i comparteix-la amb l'usuari usuari2XYZ.

**RESPOSTA**

![](comparteixcarpeta.png)



**4.13.-** Entra a Market instal·la dues aplicacions que no estiguin ja instal·lades i explica què fan i com funcionen.

![image](https://user-images.githubusercontent.com/110727546/196159706-705ff624-c409-4632-acb4-f43ffcc486d4.png)


## **RESPOSTA PRIMERA APP**


### **LA MEVA PRIMERA APLICACIÓ ÉS "CALENDAR"**

![image](https://github.com/Boby04/Acivitat4/blob/main/CALDENARI1.png?raw=true)

### **Aquesta és la seva interfes i les seves opcions per crear**

![image](https://github.com/Boby04/Acivitat4/blob/main/CALDENARI.png)

### **Podem crear tasques amb diferent color amb diferents significats per recorda que has de fer cada dia**

![image](https://github.com/Boby04/Acivitat4/blob/main/CALDENARI2.png)

### **Aquí podem veure com a quedat less tasques de "personal"**

![image](https://github.com/Boby04/Acivitat4/blob/main/CALDENARI3.png)

### **Allavors podem crear unaltre nom i unaltre color de tasca que volem fer**

![image](https://github.com/Boby04/Acivitat4/blob/main/CALDENARI4.png)

### **Aquí es pot veure com quedaria**

![image](https://github.com/Boby04/Acivitat4/blob/main/CALDENARI5.png)


## **RESPOSTA SEGONA APP**

### **En el cas de la segona app he escollit la app "Drawio"**

![](Draw.png)

### **Per fer servir aquesta aplicació ens haurem de dirigir a la pantalla inicial, i haurem de clica al icino de "+" i selecionem de crear un diagrama**

![](Draw1.png)

### **Una vegada dins, fem la faena necessaria com si fos una aplicació de digrama normal**

![](Draw2.png)

**4.14.-** Crearem una carpeta nova per emmagatzematge a Owncloud, la carpeta serà /media/publicXYZ on XYZ són les teves inicials i apareixerà amb el nom de public als usuaris.

Aquesta carpeta haurà de pertànyer a l'usuari www-data.

**RESPOSTA**


**4.15.-** Connectarem la carpeta publicXYZ com emmagatzematge local, tal i com s'indica [aquí](https://doc.owncloud.com/server/next/admin_manual/configuration/files/external_storage/local.html). Tots els usuaris tindran accés a la carpeta.

**RESPOSTA**

![](CarpetaCompartida.png)


**4.16.-** Un usuari normal pujarà un fitxer a la carpeta public.

**RESPOSTA**

![](ComandaEdita.png)

![](Text.png)

![](Emmagatzematge.png)

**COMPROVACIÓ**

![](Comprovacio.png)

**OPCIONAL.-** Aquesta tasca és opcional.

Intenta connectar com a emmagatzematge extern el teu compte de Google Drive de l'Institut. Tens com fer-ho [aquí](https://doc.owncloud.com/server/next/admin_manual/configuration/files/external_storage/google.html).

**RESPOSTA**
