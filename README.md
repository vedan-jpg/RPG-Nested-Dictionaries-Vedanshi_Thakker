# RPG-Nested-Dictionaries-Vedanshi_Thakker

#RPG 2D Arrays and Nested Dictionaries- Vedanshi_Thakker
#The Nested Dictionary; Below will print the names and ages of 4 Agents that all are a team of Ask 3 company 

characters = { # comments
    0: {
        'Tom': 'Highschool Kid and Youngest spy', #Prints the names and traits of each spy 
        'age': 17,
        },
    1: {
        'Sam': 'Boss Lady',  #Includes descriptions of their talents 
        'age': 42, #with age numbers
        },
    2: {
        'Hope': 'Smart Problem Solver', 
        'age': 21,
        },
    3: {
        'Kate': 'Loves her job and controls phone calls', #Which job each person does
        'age': 40
        },
    4: {
        'Joe': 'Big Time trouble maker never does anything right', #Traits they need to work on
        'age': 37,
        },
    }

print(characters)


inventory = { # inventory dictionary for each spy
    0: 'Spy Glasses',   #Includes lists of iteams every spy of Ask 3 carries 
    1: 'Computer and traps', 
    2: 'Money',
    3: 'Phone and spy gear',
    4: 'Special spy clothes',
    }
print(inventory)


location = { # location dictionary of where each spy agent lives and how to find them 
    0: 'Regina',
    1: 'London',
    2: 'Moose Jaw',
    3: 'Edmonton',
    4: 'Toronto',
    }
print(location)
