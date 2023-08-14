# E-Formula 전기시스템 파트 회로도 / PCB / 배선

상위 프로젝트: [luftaquila/a-fa-landing](https://github.com/luftaquila/a-fa-landing)

![image](https://github.com/luftaquila/a-fa-schematics/assets/17094868/59ae1778-9865-41a9-b81e-ef534d4b56b2)

* 회로도  
    * *EV.kicad_pro*  
       * KiCAD 6.0 프로젝트  
       * 메인 회로도입니다. 추상적으로 차량의 모든 고전압/저전압 전기 계통이 표현되어 있습니다. 메인 회로도 하위의 계층 회로도는 개별 구성 요소를 추상화합니다. 계층 회로도 중 `/PCB` 폴더 하위의 파일들은 실제 PCB의 회로도입니다.

* PCB  
    * */PCB/\*.kicad_pcb*  
       * KiCAD 6.0 PCB 아트워크  
       * 각 PCB 폴더는 하나의 독립적인 KiCAD 프로젝트입니다. 메인 회로도인 `EV.kicad_sch` 파일이 계층 회로 구성을 통해 각 PCB 폴더의 `*.kicad_sch` 파일을 가리키는 방식으로 서로 연결되어 있습니다.

* 배선  
    * *wirings*
       * 차량의 모든 외부 배선을 표현하는 [WireViz](https://github.com/formatc1702/WireViz) 배선 체계도입니다.

    ![](wirings/output/wire.png)
