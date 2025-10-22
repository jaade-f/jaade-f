<img width="1700" height="460" alt="github-header-banner (4)" src="https://github.com/user-attachments/assets/4c7d3fbe-e553-4f46-b34e-7e933b54e136" />
<p align="center"><b>Javier | Desarrollador Multiplataforma |</b></p>

## 🧑‍💻 Quien soy

👋 ¡Hola! Soy Javier, estudiante de último año del Grado Superior en Desarrollo de Aplicaciones Multiplataforma (DAM).
Durante mi formación he adquirido experiencia en desarrollo de software, programación orientada a objetos, gestión de bases de datos y gestion de equipos.

Mi objetivo es seguir creciendo como desarrollador y aplicar mis conocimientos en entornos profesionales, aportando soluciones eficientes y de calidad.

## ⚙️ Mis skills
<div align="center">

![HTML5](https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white)
<img src="https://img.shields.io/badge/java-%23ED8B00.svg?&style=for-the-badge&logo=java&logoColor=white"/> 
![Python](https://img.shields.io/badge/python-%230095D5.svg?&style=for-the-badge&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?&style=for-the-badge&logo=mysql&logoColor=white&color=3280ad)
![Git](https://img.shields.io/badge/git%20-%23F05033.svg?&style=for-the-badge&logo=git&logoColor=white&Color=c95410)
![GitHub](https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white&color=283238)
<img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="android" />
<img src="https://img.shields.io/badge/Kotlin-0095D5?&style=for-the-badge&logo=kotlin&logoColor=white" alt="kotlin" />
 

  
  ![github contribution grid snake animation](https://raw.githubusercontent.com/id1945/id1945/output/github-contribution-grid-snake-dark.svg)
  
</div>

## 🎯 Objetivos

- Terminar el Grado Superior de DAM con un proyecto sólido.
- Conseguir mis primeras prácticas o experiencia profesional en desarrollo.
- Aprender sobre arquitectura de software y buenas prácticas.
- Publicar mi primera aplicación en Android.

# ⚙️ Ejercicio ahorcado
```bash
if (palabraIntroducica == false) {
            System.out.println("Primero debes introducir una palabra");
            return;
        }
        for (int i = 0; i < palabra.length(); i++) {
            Arrays.fill(guiones, '-');
        }
        while (intentos != 0){
            System.out.println("#########################");
            System.out.println(guiones);
            System.out.println("Tienes estos intentos: " + intentos);
            System.out.println("Has introducido estas letras: " + faltan);
            System.out.println("Introduce un carcter");
            char adivinar = sc.next().charAt(0);
            faltan = faltan + " " + adivinar;

            for (int j = 0; j < guiones.length; j++) {
                char result = palabra.charAt(j);
                if (adivinar == palabra.charAt(j)) {
                    guiones[j] = adivinar;
                    aciertos = false;
                    contador++;
                    if (contador == guiones.length) {
                        System.out.println("Has acertado la palabra");
                        intentos = 11;
                        contador = 0;
                        faltan = " ";
                        palabraIntroducica = false;
                        return;
                    }
                }
            }
            if (aciertos==true) {
                intentos--;
            }
            aciertos=true;
        }
```

<img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage">

<div align="center">
<p style="font-size:24px;">MUCHAS GRACIAS</p>
</div>
