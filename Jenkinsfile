import groovy.io.FileType

def list = []

def dir = new File("D:/Jenkins/workspace/Brillio/")
dir.eachFileRecurse (FileType.FILES) { file ->
  list << file
}
