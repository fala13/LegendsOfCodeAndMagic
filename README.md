Compiled, ready to run version: https://github.com/fala13/LegendsOfCodeAndMagic_Artifacts

To compile run:
mvn package

Example uses:
# just run
java -jar -Dleague.level=4 LegendsOfCodeAndMagic-1.0.jar -p1 "python -u leg.py" -p2 "python -u leg.py" -l ./logs/game1.json

# view game in browser
java -jar -Dleague.level=4 LegendsOfCodeAndMagic-1.0.jar -p1 "python -u leg.py" -p2 "python -u leg.py" -l ./logs/game1.json -s

# Execute with 4 games with 2 threads with cg-brutaltester
java -jar .\cg-brutaltester-1.0.0-SNAPSHOT.jar -r "java -jar -Dleague.level=4 LegendsOfCodeAndMagic-1.0.jar"  -p1 "python -u leg.py" -p2 "python -u leg.py" -t 2 -n 4 -s -v -l "./logs/"

Enjoy!
