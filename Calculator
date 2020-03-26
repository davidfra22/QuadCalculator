def quadInfo(a,b,c):
	if a == 0:
		print("This is not a quadratic function. Please enter a nonzero value of a.")
	else:
		axis = -b/(2*a)
		if b**2 - 4*a*c < 0:
        print("This function has two imaginary roots and an axis of symmetry at x = " + str(axis) + ".")
		else:
			root = (-b + (b**2 - 4*a*c)**0.5)/(2*a)
			roots = (-b - (b**2 - 4*a*c)**0.5)/(2*a)
			  if root == roots:
          print("This function has one real root at x = " + str(root) + " and an axis of symmetry at x = " + str(axis) + ".")
			  else:
          print("This function has two real roots at x = " + str(root) + " and x = " + str(roots) +" and an axis of symmetry at x = " + str(axis) + ".")

quadInfo(1,15,50)
