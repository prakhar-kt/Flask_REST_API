# Flask_REST_API

This is a simple REST API built using Flask for getting and updating a movies list given below :

movies = [
    {
        'name' : 'Dune',
        'actors': [
            {
                'name' : 'Zendaya',
                'age'  : '23'
            },
            {
                'name' : 'Timothee Chalamet',
                'age'  : '26'
            }
        ],
        'ratings' : '7.2'
    },
    {
        'name' : 'The French Dispatch',
        'actors': [
            {
                'name': 'Bill Murray',
                'age' : '56'
                
            },
            {
                'name': 'Frances Mcdormand',
                'age' : '54'
            }
        ],
        'ratings' : '8.0'
    }
]

Following endpoints have been defined : 

1) GET the names of all the movies in the list
2) ADD a new movie to the list
3) GET the details of a single movie from the list
4) GET the list of the actors in a movie
5) ADD an actor to a movie in the list



