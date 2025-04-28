# Steps taken to record test metrics

Scenario: Inner City/Underground/Forest/Field
Distance: 1m/10m/30m
Number of Packages: 100/10_000/100_000
Size of Packages: 128/4096/9216

## client
- arriving at new scenario
- take photo
- create shortest distance
- put in scenario and distance 
- put in shortest package size and smallest number of packages

### cycle - distance
- increase distance - start again
- if now higher distance switch location
- test all 3 times for jitter
- put in smallest size and smallest number 
- start cycle number

#### cycle - size
- increase size - start again
- if no higher number start distance
- put in lowest number

##### cycle - number
- test all 
- tell server 
- test all 
- tell server 
- test all 
- tell server 
- increase number - start again
- if no higher number start size

## server
- arriving at new scenario
- create shortest distance
- put in scenario and distance

### cycle - distance
- put in distance
- clear results with getResults
- at every signal "Get All" and "Save All"
- when error signal press "Reload"


Number of Files per Scenario: 
Client: 27 Files 
Server: 243 Files