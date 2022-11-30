# Activitats: 

Per dibuixar els diagrames de flux podeu fer servir [draw.io](https://draw.io) o qualsevol altra eina online.

1. Calcula el CC de les següents figures:
  - ![image](https://user-images.githubusercontent.com/110727546/204613022-4ab64342-2e06-438d-a7e8-570685b3c406.png)
  - ![image](https://user-images.githubusercontent.com/110727546/204613180-6d55bf09-28b8-417e-96f4-f71a762ac44c.png)
  - ![image](https://user-images.githubusercontent.com/110727546/204655229-8c3f28d7-3d8b-4746-a55d-331f89da39d2.png)

  - **Resultat 1: 16 - 10 + 2 = 8 
  - **Resultat 2: 16 - 14 + 2 = 4
  - **Resultat 3: 8 - 6 + 2 = 4


2. Dibuixa el diagrama de flux representat per aquest codi i després calcula la seva CC:
  - ![image](https://user-images.githubusercontent.com/110727546/204615125-363e5e6c-173b-4ec0-8c0b-cb97985ade06.png)

  - **Diagrama:![image](https://user-images.githubusercontent.com/114875463/204737960-10f1f444-aa4f-4b2c-a8bb-91e7dcd9c126.png)

  - **Resultat CC: 2 + 1 = 3

3. Dibuixa el diagrama de flux representat per aquest codi i després calcula la seva CC:

```
public class proves {
    public static  String queEmPoso(int temperatura) {
        String roba = "res";
        if(temperatura<0){
           roba = "roba d'esquiar";
        }
        else if(temperatura<10){
           roba = "roba de muntanya";
        }
        else if(temperatura<20){
           roba = "roba d'hivern";
        }
        else if(temperatura<30){
           roba = "roba d'estiu";
        }
        return roba;
    }    
}
```

  - **Diagrama:![image](https://user-images.githubusercontent.com/114875463/204744374-c136f0aa-d5ef-44f2-98c0-7f237ae5b3ec.png)

  - **Resultat CC: 4 + 1 = 5
  - **Resultat proves camins: 
  A: A<0 -> A = -5 = SI // A = 4 = NO
  B: B<10 -> B = 5 = SI // B = 12 = NO
  C: C<20 -> C = 16 = SI // C = 22 = NO
  D: D<30 -> D = 27 = SI // D = 34 = NO

4. Dibuixa el diagrama de flux representat per aquest codi, calcula la seva CC i crea una prova per a cada camí posible:

```
    public static Boolean llumsEncesos(int hora) {
        Boolean llums = false;
        if(hora <= 8 || hora >= 20){
            llums = true;
        }
        return llums;
    }
```
  - **Diagrama:![image](https://user-images.githubusercontent.com/114875463/204745255-e70cbd01-bad1-4dd1-ad0e-30025af4200d.png)
  - **Resultat CC: 2 + 1 = 3
  - **Resultat proves camins:
  Hora <= 8 -> Hora = 6 = TRUE // Hora = 9 = FALSE
  Hora >= 20 -> Hora = 23 = TRUE // Hora = 17 = FALSE

5. Investiga sobre les proves de caixa negra:

  - Què són?
  - Quina diferència principal tenen sobre les de caixa blanca?
