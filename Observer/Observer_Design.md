Dart Observer Pattern
===========

옵저버패턴은 Subject 와 Observer 로 구성된다.
Subject는 Observer들에게 알림을 주고
Observer들은 하나의 Subject를 구독하는 구조이다.

유튜버와 구독자와 같이 1:다수 구조이며
느슨한 결합으로 서로 상호작용을 하지만 
Subject는 Observer을 몰라도 되고 Ovserver를 더 추가하거나
변화해도 영향을 받지 않는다
