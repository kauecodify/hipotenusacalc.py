# hipotenusacalc.py
import math

def pitagoras (cat1, cat2, hip):

  if hip == '?':
    hip = (cat1**2+cat2**2)**(1/2)
      print ('A hipotenusa é', hip)

  elif cat1 =='?':
    cat1 = (hip**2-cat2**2)**(1/2)
        print ('O cateto é', cat1)
  elif cat2 =='?':
    cat2 = (hip**2-cat1**2)**(1/2)
      print ('O cateto é', cat2)
                # debbug > pitagoras (13,5,'?')
