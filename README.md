
# Google developers console setup

1)Open Google Developer's console (https://console.developers.google.com/) <br/>
2)Create a new project <br/>

![Screenshot (41)_LI](https://user-images.githubusercontent.com/82023206/147849291-362031f2-badc-4b9e-81d9-b535bdd54d7e.jpg) <br/>
![Screenshot (42)](https://user-images.githubusercontent.com/82023206/147849306-d889a321-38b8-4b57-a6bd-02f865e68e25.png) <br/>
![Inkednew_LI](https://user-images.githubusercontent.com/82023206/149916163-dfe6177a-9056-43d2-8a35-066a3ab882fa.jpg) <br/>

5)Enable Google Calendar Api. <br/>
![Screenshot (43)_LI](https://user-images.githubusercontent.com/82023206/147849319-36ca1afd-4cbf-4526-8876-623afd67dbf7.jpg)
![Screenshot (44)](https://user-images.githubusercontent.com/82023206/147849321-76a88269-aab1-43fc-82ee-1d4580d4de54.png)
![Screenshot (45)](https://user-images.githubusercontent.com/82023206/147849323-cfc5e260-7ba0-452a-ba96-c937a175e47b.png)

6)Click on Create credentials --> create Api Key.   <br/>
![Screenshot (47)_LI](https://user-images.githubusercontent.com/82023206/147850090-eb56e560-cac3-4ae3-9325-7de78ddaba69.jpg)

7)Setup OAuth consent screen <br/>
![Screenshot (48)_LI](https://user-images.githubusercontent.com/82023206/147850108-fe58463a-c993-417c-be17-457588b3614d.jpg)
    >Configure Consent Screen <br/>
    >Configure Scopes [optional] <br/>
    >Add Test Users <br/>
    >Summary of settings <br/>
   ![Screenshot (50)](https://user-images.githubusercontent.com/82023206/147850129-8a6447a8-c9d6-4c24-8724-87a6c0184c4a.png)
![Screenshot (51)](https://user-images.githubusercontent.com/82023206/147850130-64c09c1d-71d5-4cd6-84a6-b1f07385d3e2.png)
![Screenshot (52)](https://user-images.githubusercontent.com/82023206/147850132-e4b830d1-f694-478c-9fed-bc8f3c16e809.png)
![Screenshot (53)](https://user-images.githubusercontent.com/82023206/147850133-1ec01b0e-3897-433d-9fea-e457a8af3d58.png)
![Screenshot (54)](https://user-images.githubusercontent.com/82023206/147850134-b6621dfc-1caa-42a7-a108-3cb9b1c334d0.png)
![Screenshot (55)](https://user-images.githubusercontent.com/82023206/147850135-f8b6eb1f-a03d-48f7-90de-5babaad4e99a.png)
![Screenshot (56)](https://user-images.githubusercontent.com/82023206/147850136-298db646-6b80-4583-ace4-f5316f802c8f.png)

8)Click on create credentials <br/>
![Screenshot (49)_LI](https://user-images.githubusercontent.com/82023206/147850146-a42e88de-789e-4141-9ecb-e92d9dbb3472.jpg)

   To get OAuth ID <br/>
    Download and install Opensll at this link ::<br/>
  
  https://slproweb.com/products/Win32OpenSSL.html <br/>
    If you face any difficulties watch this video<br/>
    https://www.youtube.com/watch?v=jSkQ27sTto0 <br/>
   
   ![open](https://user-images.githubusercontent.com/82023206/149928330-34685ac2-8ef7-42ac-95ff-60388cf97198.jpg) <br/>
    
  After installation
    
  1:Setup Environment variable [Add new Path > C:\Program Files\OpenSSL-Win64\bin ] 
  2:Open cmd and run these commands shown in the picture below 
  
    
   Create OAuth client ID <br/>
    Visit this link to create OAuth client ID for an Expo app https://docs.expo.dev/versions/latest/sdk/google/ <br/>
    
![Screenshot (58)](https://user-images.githubusercontent.com/82023206/147850156-27d3db92-f602-4638-9146-cd57babcbbc1.png)

![Screenshot (57)](https://user-images.githubusercontent.com/82023206/147850154-379839d1-fcb3-4d84-aa37-73f6ec3f11e4.png)
![Screenshot (59)](https://user-images.githubusercontent.com/82023206/147850157-4b9295f2-48d7-4094-b6f7-b953d528f2d6.png)

9)Copy Api Key and Client ID generated to the config file in the project <br/>

# Getting Calendar ID <br/>
1)Get Calendar ID from your google calendars and paste it in config file <br/>
![Screenshot (60)](https://user-images.githubusercontent.com/82023206/147850162-b2787ecd-ece2-4653-8479-aa1f1f2c96d8.png)
![Screenshot (61)](https://user-images.githubusercontent.com/82023206/147850163-57696386-7ee6-46f5-8318-642b7a266bd9.png)


# Setting up the project
1)Install all of the libraries <br/>


Note :: You can use "yarn" to install libraries
