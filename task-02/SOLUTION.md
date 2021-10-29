mkdir Coordination-Location
cd Coordination-Location
mkdir North
cd North
touch NDegree.txt
vim NDegree.txt
9° and then :w and then :x
touch NMinutes.txt
5' and then :w and then :x
touch NSeconds.txt
2.1 and then :w and then :x
cat NDegree.txt NMinutes.txt NSeconds.txt > NorthCoordinate.txt
cd Coordination-Location
cp /home/sreeram/Coordination-Location/North/NorthCoordinate.txt /home/sreeram/Coordination-Location
mv NorthCoordinate.txt North.txt
cd North
rm NorthCoordinate.txt
cd Coordination-Location
mkdir East
cd East
touch EDegree.txt
vim EDegree.txt
76° and then :w and then :x
touch EMinutes.txt
vim EMinutes.txt
29' and then :w and then :x
touch ESeconds.txt
30.8" and then :w and then :x
cat EDegree.txt EMinutes.txt ESeconds.txt > EastCoordinate.txt
cd Coordination-Location
cp /home/sreeram/Coordination-Location/East/EastCoordinte.txt /home/sreeram/Coordination-Location
mv EastCoordinate.txt East.txt
cd East
rm EastCoordinate.txt
cd Coordination-Location
cat North.txt East.txt > Location-Coordinates.txt

