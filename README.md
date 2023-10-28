## Announcement

## Assignment 2
### Due Date: 31.10.2023 @ 23:50
Explicitly design and show the below equation on our Design Simulator.

**Equation F = ABC+A'BC**

## Tasks
1- Complete the Truth Table of the equation.  
2- Implement equation by using minimum amount of logic gates.  
4- Carefully name the inputs and the outputs of the circuit. Write explanation if necessary.
3- Save and Upload your circuit Digital design file to the repo like **Example-Circuit.dig**. 

## Equipment List: 
1- 74LS32 TTL OR GATE IC  
2- 74LS08 TTL AND GATE IC  
3- 74LS04 TTL NOT GATE IC  
4- Standard set equipments  

### Screenshots

![Truth table Assignment 2](https://github.com/abbaselmas/Assignment/assets/148693774/641a5900-429d-43d5-84d6-583d73336552)
![Circuit](https://github.com/abbaselmas/Assignment/assets/148693774/36a8fa5d-bf64-4424-8ed9-b39adbe49c54)

If we simplify this equation F = ABC+A'BC , we are left with this result BC(A'+A) and A'+ A means 1 so ABC+A'BC= BC and  we can represent this equation in circuit form as follows

![circuit 2](https://github.com/abbaselmas/Assignment/assets/148693774/f1070a60-3ad0-47da-b02b-49978da441b0)

[Upload<?xml version="1.0" encoding="utf-8"?>
<circuit>
  <version>2</version>
  <attributes/>
  <visualElements>
    <visualElement>
      <elementName>In</elementName>
      <elementAttributes>
        <entry>
          <string>Label</string>
          <string>A</string>
        </entry>
      </elementAttributes>
      <pos x="360" y="140"/>
    </visualElement>
    <visualElement>
      <elementName>In</elementName>
      <elementAttributes>
        <entry>
          <string>Label</string>
          <string>B</string>
        </entry>
      </elementAttributes>
      <pos x="360" y="280"/>
    </visualElement>
    <visualElement>
      <elementName>In</elementName>
      <elementAttributes>
        <entry>
          <string>Label</string>
          <string>C</string>
        </entry>
      </elementAttributes>
      <pos x="360" y="420"/>
    </visualElement>
    <visualElement>
      <elementName>Out</elementName>
      <elementAttributes>
        <entry>
          <string>Label</string>
          <string>F</string>
        </entry>
      </elementAttributes>
      <pos x="940" y="280"/>
    </visualElement>
    <visualElement>
      <elementName>And</elementName>
      <elementAttributes>
        <entry>
          <string>wideShape</string>
          <boolean>true</boolean>
        </entry>
        <entry>
          <string>Inputs</string>
          <int>3</int>
        </entry>
      </elementAttributes>
      <pos x="500" y="180"/>
    </visualElement>
    <visualElement>
      <elementName>Or</elementName>
      <elementAttributes>
        <entry>
          <string>wideShape</string>
          <boolean>true</boolean>
        </entry>
      </elementAttributes>
      <pos x="700" y="260"/>
    </visualElement>
    <visualElement>
      <elementName>And</elementName>
      <elementAttributes>
        <entry>
          <string>wideShape</string>
          <boolean>true</boolean>
        </entry>
        <entry>
          <string>Inputs</string>
          <int>3</int>
        </entry>
      </elementAttributes>
      <pos x="540" y="360"/>
    </visualElement>
    <visualElement>
      <elementName>Not</elementName>
      <elementAttributes>
        <entry>
          <string>rotation</string>
          <rotation rotation="3"/>
        </entry>
      </elementAttributes>
      <pos x="440" y="160"/>
    </visualElement>
    <visualElement>
      <elementName>NotConnected</elementName>
      <elementAttributes/>
      <pos x="500" y="360"/>
    </visualElement>
    <visualElement>
      <elementName>NotConnected</elementName>
      <elementAttributes/>
      <pos x="500" y="380"/>
    </visualElement>
    <visualElement>
      <elementName>NotConnected</elementName>
      <elementAttributes/>
      <pos x="440" y="280"/>
    </visualElement>
  </visualElements>
  <wires>
    <wire>
      <p1 x="500" y="400"/>
      <p2 x="540" y="400"/>
    </wire>
    <wire>
      <p1 x="360" y="420"/>
      <p2 x="500" y="420"/>
    </wire>
    <wire>
      <p1 x="360" y="280"/>
      <p2 x="400" y="280"/>
    </wire>
    <wire>
      <p1 x="780" y="280"/>
      <p2 x="940" y="280"/>
    </wire>
    <wire>
      <p1 x="400" y="280"/>
      <p2 x="480" y="280"/>
    </wire>
    <wire>
      <p1 x="480" y="200"/>
      <p2 x="500" y="200"/>
    </wire>
    <wire>
      <p1 x="580" y="200"/>
      <p2 x="700" y="200"/>
    </wire>
    <wire>
      <p1 x="440" y="360"/>
      <p2 x="540" y="360"/>
    </wire>
    <wire>
      <p1 x="360" y="140"/>
      <p2 x="440" y="140"/>
    </wire>
    <wire>
      <p1 x="440" y="140"/>
      <p2 x="500" y="140"/>
    </wire>
    <wire>
      <p1 x="620" y="300"/>
      <p2 x="700" y="300"/>
    </wire>
    <wire>
      <p1 x="400" y="380"/>
      <p2 x="540" y="380"/>
    </wire>
    <wire>
      <p1 x="480" y="200"/>
      <p2 x="480" y="280"/>
    </wire>
    <wire>
      <p1 x="400" y="280"/>
      <p2 x="400" y="380"/>
    </wire>
    <wire>
      <p1 x="500" y="140"/>
      <p2 x="500" y="180"/>
    </wire>
    <wire>
      <p1 x="500" y="220"/>
      <p2 x="500" y="400"/>
    </wire>
    <wire>
      <p1 x="500" y="400"/>
      <p2 x="500" y="420"/>
    </wire>
    <wire>
      <p1 x="440" y="140"/>
      <p2 x="440" y="160"/>
    </wire>
    <wire>
      <p1 x="440" y="200"/>
      <p2 x="440" y="360"/>
    </wire>
    <wire>
      <p1 x="700" y="200"/>
      <p2 x="700" y="260"/>
    </wire>
    <wire>
      <p1 x="620" y="300"/>
      <p2 x="620" y="380"/>
    </wire>
  </wires>
  <measurementOrdering/>
</circuit>ing Example-Circuit.dig…]()

