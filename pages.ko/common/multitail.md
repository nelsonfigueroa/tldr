# multitail

> tail의 확장판.
> 더 많은 정보: <https://manned.org/multitail>.

- 패턴과 일치하는 모든 파일을 하나의 스트림에서 보여주기:

`multitail -Q 1 '{{패턴}}'`

- 디렉터리의 모든 파일을 하나의 스트림에서 보여주기:

`multitail -Q 1 '{{경로/대상/폴더}}/*'`

- 새 파일을 자동으로 창에 추가:

`multitail -Q {{패턴}}`

- 5개의 로그 파일을 표시하고 2개를 병합하여 2개의 열에 넣되, 왼쪽 열에는 하나만 배치:

`multitail -s 2 -sn 1,3 {{경로/대상/병합파일}} -I {{경로/대상/파일1}} {{경로/대상/파일2}} {{경로/대상/파일3}} {{경로/대상/파일4}}`
