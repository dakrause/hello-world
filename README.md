# hello-world
Simple repository to learn GitHub concepts
Here is some new material to add to my hello-world repository.
I am pasteing some code as follows:

def hexStr(byteList):
    """
    Convert a list of byte integers (0 - 255) to a text string of 2-digit
    hex values separated by spaces.  The byteList argument may be either a
    list of normal integers or a bytearray.  For example,
    hexStr([2, 17, 255, 0xFF]) returns '02 11 ff ff'.
    """
    hexString = u''
    for byte in byteList:
        hexString += u'%02x ' % byte
    return hexString[:-1]
