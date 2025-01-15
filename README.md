
# EigenGhosts - ISEP IPP PT

EigenGhost is a algorithm using algebra that makes the user to be able to: 
Please take note the higher the number of own values the better will be the fidelity of the image

#### Functionality one [DECOMPOSE] -> 
It takes as parameters: "Own values"; ".csv file"

A = P D Pᵀ
   - P is a matrix whose columns are unit eigenvectors of A;
   - D is a diagonal matrix whose elements are the eigenvalues associated with the eigenvectors of A;
   - Pᵀ is the transpose of the matrix P. 

> Returns this information. *[Not really useful]*

#### Functionality two [RECONSTRUCT DATABASE] -> 
>It takes as parameters: *"Own values"; "directory with .csv AKA database"*


![image](https://github.com/user-attachments/assets/9a2f4575-f9c4-4ece-939e-d91e0026aaeb)

Fully reconstructs an image database 

#### Functionality three [SEARCH CLOSEST] -> 
It takes as parameters: *"Own values"; "directory is .csv AKA database"; "the image that you want to search "* 

> Looks into the database to search the closest image to the one you specified

#### Functionality four [CREATE A RANDOM IMAGE]-> 
It takes parameters *"Own values"; "directory is .csv AKA database";*

> Get a random image based on the average of all the images in the database

## Installation

Use the library [Apache Math 3.6.1](https://mvnrepository.com/artifact/org.apache.commons/commons-math3/3.6.1) to install the dependencies.

## Usage

Running the code in an interactive mode (Not using arguments)
```java
java -jar EigenGhosts.jar
```

Running the code in an non interactive approach (Using arguments)
```java
java -jar EigenGhosts.jar -h #!! ASK FOR HELP !!
```
> You will get a full tutorial on how to use it. However you might take note of the following

-f X -k Y -i Z -d W

X -> Functionality number

Y -> Quantity of own values

Z -> Image path (.csv)

W -> Directory path [Also refered as database]

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Colaborators
[Bernardo Correia](https://github.com/BKTales)

[Tiago Lima](https://github.com/Tiago-Lima-TSL)

[Eduardo Vasconcelos](https://github.com/eduVVSC)

[Rodrigo Junqueira](https://github.com/junkeira13)

## License

[MIT](https://choosealicense.com/licenses/mit/)




