El objetivo del parametro package que se le suministra a mvn permite empaquetar toda la informacion en un .jar para que pueda ser ejecutado 
Aparte del que ya conocemos que es jar, tambuen evisten; clear, compile, instalar, deploid y site entre otros.

mvn exec:java -Dexec.mainClass="edu.eci.cvds.patterns.App"

![image](https://user-images.githubusercontent.com/123812969/219272306-b5307189-f5a5-463c-9dbb-351a8d7cdbd7.png)

mvn exec:java -Dexec.mainClass="edu.eci.cvds.patterns.App" -Dexec.args="jordy"

![image](https://user-images.githubusercontent.com/123812969/219272388-498210e1-29f9-411e-a789-8d3dffee2ee5.png)

mvn exec:java -Dexec.mainClass="edu.eci.cvds.patterns.App" -Dexec.args="jordy Bautista"

![image](https://user-images.githubusercontent.com/123812969/219432055-67b244b6-183e-4dd4-9864-6811712bbdd6.png)

