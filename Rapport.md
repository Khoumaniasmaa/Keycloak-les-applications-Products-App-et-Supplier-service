# Keycloak les applications Products-App (Frontend avec thymeleaf) et Supplier-service (Micro-service backend)

Partie 2: How To Secure Distributed Systems with KEYCLOAK - Keycloak Spring Security Integration

   ---------------------------------------------------Configurer KEYCLOAK------------------------------------------------

1- Creation un client "Products-app"

![Screenshot_11](https://user-images.githubusercontent.com/84717947/203623048-22636f1a-1587-4ed3-ae9c-d1460ae8be41.png)

2-Creation les users:

![Screenshot_13](https://user-images.githubusercontent.com/84717947/203623055-352ae082-742d-4e3e-a7e7-ea1200f6bc97.png)

3-Affectaion chaque utilisateurs a son roles

![Screenshot_14](https://user-images.githubusercontent.com/84717947/203623057-10440ec9-1b81-4119-be15-27e54908010a.png)

4-	Enoyez un request http de type post dans Advenced rest client : 

![image](https://user-images.githubusercontent.com/84717947/203622746-27885911-50a5-4306-8757-ed0f76d75c68.png)

5-	Acces token  dans jwt.io  de user 1:

![image](https://user-images.githubusercontent.com/84717947/203622789-98e01d57-0090-47a6-bd80-a084b479f6a4.png)

6-	Fresh token  de user 1 :

![image](https://user-images.githubusercontent.com/84717947/203622847-65de7bd7-a5b8-40fa-82ec-0cd7c053bd7d.png)

7-	On a changer time de acces token par =10min :

![image](https://user-images.githubusercontent.com/84717947/203622903-12a14c15-44a8-4614-be48-47a9fe2011a3.png)
 
       =>Acces token pour user 2

![image](https://user-images.githubusercontent.com/84717947/203622963-a5384101-4f22-413f-86ec-d3d6d040e5c7.png)

      =>	Au cas de token expirée :

![image](https://user-images.githubusercontent.com/84717947/203622999-867cd429-a1bc-4982-8d0d-5bc478ba14f4.png)

---------------les applications Products-App (Frontend avec thymeleaf) et Supplier-service (Micro-service backend)----------------------![Screenshot_19](https://user-images.githubusercontent.com/84717947/203654486-da072c3a-7a13-410f-8047-f8553fa2315d.png)


         ------------------------------------------------Avant de securiser-----------------------------------------

8-Products:

![Screenshot_15](https://user-images.githubusercontent.com/84717947/203635937-c770ace7-1027-483c-9b28-6da883995910.png)

9-Suppliers:

![Screenshot_16](https://user-images.githubusercontent.com/84717947/203635944-65e520f9-974f-4274-85c1-59602d80c1b4.png)

                                            ----------------Partie 3-------------------------------
                                            
10-Récupperer acces token par (/jwt)

![Screenshot_19](https://user-images.githubusercontent.com/84717947/203831245-243c8d1f-2c6f-4f6c-8822-0ff7b72ee5eb.png)

11- connecter avec user 3: 

![Screenshot_23](https://user-images.githubusercontent.com/84717947/203847276-f67fcec7-3b56-4092-b237-83e0fd7010eb.png)

![Screenshot_22](https://user-images.githubusercontent.com/84717947/203847299-eada3a92-67ac-408b-bb64-fb7c01359212.png)

12-connecter avec user 1:

![Screenshot_20](https://user-images.githubusercontent.com/84717947/203847380-144eee60-9d26-48dd-b403-46d2f8f04ab0.png)

![Screenshot_21](https://user-images.githubusercontent.com/84717947/203847332-3023c8ea-49c7-4440-8ee8-9dc730c2c4f5.png)

13-Donner droit d' utilisateur d'inscrire:

 -Inscrire:
 
![Screenshot_25](https://user-images.githubusercontent.com/84717947/203848339-1452250e-8916-4eff-ac0d-2b537b1391bc.png)

-Register:
![Screenshot_26](https://user-images.githubusercontent.com/84717947/203848775-bb92065a-c6de-46b4-a8c5-0c6a7df5439d.png)

14-Donner  a l'utilisateur khoumani asmaa droit de MANAGER:

![Screenshot_27](https://user-images.githubusercontent.com/84717947/203848842-3e534eb8-30e4-4f67-96da-dd5d8623d6a2.png)

![Screenshot_28](https://user-images.githubusercontent.com/84717947/203848845-8d277720-0bfd-4c63-99b0-5e6990ecfc13.png)

15-Configuration de Password:

![Screenshot_29](https://user-images.githubusercontent.com/84717947/203849262-bb79d332-0af1-4c8f-9d11-8f1587cb1c94.png)

16- Configure OTP pour l utilisateur Khoumani asmaa:

![Screenshot_30](https://user-images.githubusercontent.com/84717947/203850048-ee9a7e96-0f38-4d4b-992c-8b067dbfb8ec.png)

17-Changer le mot de passe:

![Screenshot_32](https://user-images.githubusercontent.com/84717947/203852694-9263b686-ac3e-4ae0-97c7-ce7b3be87bcd.png)



