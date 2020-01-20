# MTD Project

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

파일명은 전부 소문자, 공백없이, 언더바(_)로 구분
mininet_topolgy 코드는 파일명 앞에 "topo_"로 시작.
컨트롤러 코드는 파일명 앞에 "RYU_"로 시작.
뒤에 오는 이름은 topolgy와 컨트롤러 코드와 결합하여 사용할 경우 이름을 똑같이 구성 스위치 갯수, 호스트 갯수로 구성해도됨(topo_4host2switch.py)

## 예제
 - topo_singlerouter.py
 - ryu_singlerouter.py
 - topo_2switch6hosts.py




### execute

example_Topology/topo_simplerouter.py
단일 파일, Host5, Switch2, Router2

```sh
$ sudo python topo_simplerouter.py
```
```python
mininet > h1 ping -c 1 h4
```
-----
### execute ryu_shortestpath.py
```sh
$ ryu-manager ryu_shortestpath.py --observe-links
```
and open new terminal
```sh
$ sudo mn --topo tree,3 --controller=remote --switch ovsk
```
------
## Directories

 - Circular_Topology
 - Tree_Topology
 - example_Topology
 ------
### Todos

 - Write MORE Tests
 - PLUS our own IDEA!

License
----

MIT


**Free Software, Hell Yeah!**

#### You can also:
 - 
# New Features!

  - 마크다운 언어 사용법 익히기


> The overriding design goal for Markdown's
> formatting syntax is to make it as readable
> as possible.