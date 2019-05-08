#python
#Color Mixer
#Ask a user to input the name of primary colors

def main():
    
    color1 = input (" Enter the name of primary color 1: ")
    color2 = input (" Enter the name of primary color 2: ")
    
    print ()
  
    if (color1 == "red" and color2 == "blue")or \
        (color1 == "blue" and color2 == "red"):
        print (color1 + " mixed with " + color2 + " is purple. " )
        
    elif (color1 == "red" and color2 == "yellow")or \
        (color1 == "yellow" and color2 == "red"):
        print (color1 + " mixed with " + color2 + " is orange. " )
        
    elif (color1 == "blue" and color2 == "yellow")or \
        (color1 == "yellow" and color2 == "blue"):
        print (color1 + " mixed with " + color2 + " is green. " )
        
    else:
        print ('ERROR: Please enter only the primary color',\
               'that are red, blue and yellow.')

main()
