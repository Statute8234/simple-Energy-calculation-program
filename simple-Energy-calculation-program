class Object:
    def __init__(self, wight,distance):
        self.wight = wight
        self.distance = distance
        gravity = 0.00220462
        self.J = ((wight/454) * gravity) * distance

wight, distance = float(input('The wight of the object in libs > ')),float(input('The distance between point A and B in metters > '))
object = Object(wight, distance)

print()

print('you need',object.J,'joules of energy to move the object {} meters'.format(distance))
