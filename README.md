class Flower :
    def __init__(self, petalName, petalNumber, petalPrice) :
           self.name = petalName
           self.petal = petalNumber
           self.price = petalPrice
    def setName(self,petalName):
           self.name = petalName
    def setPetal(self,petalNumber):
           self.petal = petalNumber
    def setPrice(self,petalPrice):
           self.price = petalPrice
    def getName(self):
           return self.name
    def getPetal(self):
           return self.petal
    def getPrice(self):
           return self.price
 f1 = Flower ("Rose",6,200)
 print ("Flower Details:")
 print ("Name :",f1.getName())
 print ("Number of Petals:",f1.getPetal())
 print ("Price :",f1.getPrice())
 print ("\n")
 f2 = Flower ("Lotus", 4, 500)
 print ("Flower Details:")
 print ("Name :",f2.getName())
 print ("Number of Petals:",f2.getPetal())
 print ("Price :",f2.getPrice())
 print ("\n")
 f2.setName("Sunflower")
 f2.setPrice(1200)
 f2.setPetal(8)
 print ("Flower Details:")
print ("Name :",f2.getName())
 print ("Number of Petals:",f2.getPetal())
 print ("Price :",f2.getPrice())
 print ("\n")
