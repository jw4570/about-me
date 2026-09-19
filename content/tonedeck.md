# ToneDeck

컴퓨터 키보드를 피아노처럼 사용해 다이아토닉 스케일과 코드를 연주하는 macOS 도구입니다.

## 주요 기능
- MIDI 출력 장치 선택과 가상 MIDI 소스
- Key, Scale, Chord, Voicing 설정
- 아르페지에이터와 BPM 조절
- 서스테인, 피치 벤드, 모듈레이션
- 연주 강도와 타이밍에 변화를 주는 Humanize
- 모든 음을 끄는 Panic 동작과 투명 연주 모드

## 기술
`SwiftUI`로 인터페이스를 만들고, `AppKit` 키보드 이벤트와 `CoreMIDI`를 이용해 연주 입력과 MIDI 출력을 처리했습니다.
