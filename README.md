# reCamera_Gimbal-OpenClaw
Use OpenClaw to control the motor, speaker, microphone, LED, and camera of the reCamera Gimbal.  
使用OpenClaw来控制reCamera Gimbal的电机、扬声器、麦克风、LED和摄像头。


I uploaded the JSON file for the reCamera Gimbal, which you can import into Node-RED, and I have opened two HTTP interfaces, one for controlling the dual-motor angle of the reCamera Gimbal and one for taking photos, such as http://192.168.1.2:1880/api/gimbal?yaw=90&pitch=45 and http://192.168.1.2:1880 / api / photo.  
我上传了reCamera Gimbal的JSON文件，你可以在Node-RED中进行导入，并且我开放了两个http接口，分别用于控制reCamera Gimbal的双电机角度和拍照，例如http://192.168.1.2:1880/api/gimbal?yaw=90&pitch=45和http://192.168.1.2:1880/api/photo

As for Skills, I am currently writing the Chinese version, but it does not affect the operation of OpenClaw. I mean that if you directly use English or other languages to communicate with OpenClaw to control the reCamera Gimbal, it is also possible. If you want to write Skills yourself, please refer to the Skills writing specification https://agentskills.io/specification#allowed-tools-field  
至于Skills，我目前写的是中文版本的，但是它并不影响OpenClaw的操作，我是指如果你直接使用英文或者其他语言直接和OpenClaw交流来控制reCamera Gimbal也是可以的。如果您想自己编写Skills，请查看Skills编写规范https://agentskills.io/specification#allowed-tools-field
