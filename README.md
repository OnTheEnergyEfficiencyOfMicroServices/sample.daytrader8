# How to Deploy

1. Maven
```
sudo apt install maven -y
```

2. Java
```
sudo apt install openjdk-21-jdk -y
```

3. Download
```
git clone https://github.com/OnTheEnergyEfficiencyOfMicroServices/sample.daytrader8.git
```

4. Run
```
cd sample.daytrader8
```
```
mvn clean package liberty:run
```

http://localhost:9080/daytrader

<hr>

5. Different port
```
mvn clean package liberty:run -DtestServerHttpPort=9081
```

## Notice

© Copyright IBM Corporation 2019.

## License

```text
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
````
