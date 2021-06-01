## Flappy-Bird

- A java program for the unfamous flappy bird classic arcade game.
- To run 
	* Clone this repository.
	* Run this
		```bash
		java -jar FlappyBird.jar
		```

- Compiling jar file from source.
	```bash
	echo "Main-Class: src/flappyBird/FlappyBird" > manifest.txt
	jar cvmf manifest.txt FlappyBird.jar ./src/flappyBird/*.class ./render/*.class
	```
* ![Demo](play.mov)
