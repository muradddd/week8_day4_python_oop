Asagidaki class-i yaradin.

class Vehicle:

	numofWheels;
	color;
	engine;
	positionX;
	positionY;
	speed; 

isOn = false;

initialize Vehicle();

set values:

		color
		engine
		numofWheels

accelerate() - Bu funksiya cagirilarken masinin suretini 1 vahid artirin

moveForward(int x, int y) - bu function cagirilarken masinin postionX ve PostionY deyerlerini musbete dogru deyisin

moveBackwards(int x, int y) - bu function cagirilarken masinin postionX ve PostionY deyerlerini menfiye dogru deyisin

ignition() - bu method masin On-dursa Off, Off-dursa On halina getirmelidir

getNumofWheels() - bu method tekerlerin sayini qaytarmalidir

setNumofWheels(int num) bu method tekerlerin sayini deyislemelidir

getColor() - bu method masinin rengini qaytarmalidir

setColor(Color color) - bu method masinin rengini deyismelidir

__str__() - bu method masin haqqinda melumatlari print etmelidir
