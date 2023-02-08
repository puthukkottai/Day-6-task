class circle {
//member varibles
privayte radius: number;
 
// constructor
constructure(radius: number) {
    this.radius = radius;
}

//member functions
getRadius(): number {
     return this.radius;
}

setRadius(radius: number); void {
     this.radius = radius;
}

getDiamler(): number {
     return this.radius *2;
}

getCircumference(): number {
    return 2*Math.PI*this.radius;
}
getArea(): number {
     return Math.pI*this.radius*this.radius;
}
}