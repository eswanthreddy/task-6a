# task-6a
def writefile(filename):
    """Writes a string to the file."""
    with open(filename, "w") as f:
        f.write("Error objects are thrown when runtime errors occur. The Error object can also be used as a base object for user-defined exceptions.")

def readfile(filename):
    """Reads and prints the content of a file."""
    with open(filename, "r") as file:
        content = file.read()
        print(content)

# Write to the file
writefile("log.txt")

# Read from the file
readfile("log.txt")

