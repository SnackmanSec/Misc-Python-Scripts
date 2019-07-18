with open('C:\\Users\username\Desktop\list1.txt', 'r') as fileA:
    fileA_set = set()
    for line in fileA:
        fileA_set.add(line)

    with open('C:\\Users\username\Desktop\list2.txt', 'r') as fileB:
        fileB_set = set()
        for line in fileB:
            fileB_set.add(line)

        problemSet = fileA_set.intersection(fileB_set)

        print (len(problemSet) == 0)
