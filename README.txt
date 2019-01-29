This is a java maven project, to compile use the command(that is of course you have maven installed):
->mvn clean package
How to run the project:
Under each component there is a target folder which contains a jar file.
Start with the router: java -jar <filename>.jar
Secondly, the market: java -jar <filename>.jar 10 10 //the parameters are price and quantity
thirdly, the broker: java -jav <filename>.jar <marketId> 1 //the marketId comes from the server to the market component as soon as you run the market component... every client that connects to the router gets an id
Lastly, watch the magic happen...
