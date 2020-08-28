import os
import pyttsx3 as p3

p3.speak("Hello User, Please enter your NAME")
x=input("enter the NAME:\n")
p3.speak("Hello"+ x)
p3.speak("WelCome to my Software")
p3.speak("Tell me about Your OPERATING SYSTEM")

y=input("Enter your OPERATING SYSTEM:\n")
   
if ('windows'in y.lower()):
      p3.speak("Scanning the Windows for Few seconds")
      print("Completed Scanning of Windows")
      os.system('timeout 4')
      
elif ('linux'in y.lower()):
      p3.speak("Scanning the linux for few seconds")
      print("Completed scanning of linux")
      os.system('timeout 4')
      
elif (('mac'in y.lower()) or('macos'in y.lower())):
      p3.speak('Scanning the macos or mac for few seconds')
      print("completed  Scanning of mac or macos")
      os.system('timeout 4')
else:
        p3.speak('Scanning Your Operating System')
        print("Completed Scanning of Oerating System")
        os.system('timeout 4')        
      
p3.speak("How can I help you in my software")
 
while True:
  
  p3.speak("tell me Your Requirement")
  a=input("Tell me your requirement:\n")
  
  if(('run' in a.lower())or ('activate'in a.lower())or('excute'in a.lower())or('chrome' in a.lower())or('browser' in a.lower())or('searching'in a.lower())or('new things'in a.lower())):
        p3.speak("Opening Chrome Enjoy it")
        os.system('timeout 3')
        os.system('chrome')
   
  elif(('run'in a.lower())or ('activate'in a.lower())or ('excute'in a.lower())or('notepad'in a.lower())or('editor'in a.lower())):
        p3.speak("Opening Notepad Enjoy it")
        os.system('timeout 3')
        os.system('notepad')
   
  elif(('run'in a.lower())or ('activate'in a.lower())or ('excute'in a.lower())or('Proteus Softwer'in a.lower())or('simulation'in a.lower())):
        p3.speak("opening the Proteus Software for simulation")
        os.system('timeout 3')
        os.system('PDS')

  elif(('run'in a.lower())or ('activate'in a.lower())or('excute'in a.lower())or ('Telegram'in a.lower())or('chat'in a.lower())):
        p3.speak("Opening the  Telegram for chat Enjoy it")
        os.system('timeout 3')
        os.system('telegram')
    
  elif(('run'in a.lower())or ('activate'in a.lower())or('excute'in a.lower())or('Paint'in a.lower())or('Drawing'in a.lower())):
        p3.speak("Opening the Paint for Drawing")
        os.system('timeout 3')
        os.system('mspaint')
  
  elif(('exit'in a.lower())or ('stop'in a.lower())):
        print()
        print("Thank You for Using Software")
        p3.speak("Thank You"+ x + "Have a Nice Day")
        break    
   
  else:
        p3.speak("Sorry,I cannot Open this on your Device")
        p3.speak("Please enter the Correct spelling")
        
        



        
        
                
     



