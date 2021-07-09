# 데모크라시 4 한글 번역

English는 영어 원문 파일이 있는 참고용 폴더이며 Korean 폴더 안에 있는 파일을 번역 또는 검수하셔야 합니다.

현재 사람 손이 닿은 적이 없는 한글 텍스트는 없지만 소수의 인원으로 작업을 했기 때문에 추가적인 검수가 필요합니다.

names 폴더 안에는 설치경로의 Democracy 4\data\names 폴더에 덮어씌워 이름 생성시 영문 대신 한글로 이름이 생성되게 해주는 텍스트가 들어있습니다.

창작마당 링크: https://steamcommunity.com/sharedfiles/filedetails/?id=2423985186

# 번역 규칙

misson 폴더 안에 있는 파일과 partynames, strings 파일을 제외한 파일은 두번째 쉼표가 찍힌 이후의 내용을 번역해주시면 됩니다.
대부분 두번째 쉼표 이후는 '제목'이고 세번째 쉼표 이후는 '내용'입니다. 현재 quotes.csv를 제외한 나머지는 번역이 완료된 문자열이 대다수를 차지하고 있으니 번역을 새로 할 때는 기존 문자열을 참고하시면 됩니다.

예시)

> #,AdultEducationSubsidies,성인 교육 보조금,성인 교육 보조금은 근로자가 취업한 후에도 재교육과 학습을 지속할 수 있도록 유도하는 방안이다. 보조금의 지급대상으로는 야간 수업 수강생이나 원격학습 자료 이용자 등이 포함된다. 이러한 제도는 노동자의 전반적인 교육 수준을 높이는 데 도움이 된다.
> 
> [policies.csv](./Korean/policies.csv)

|#|스트링명|정책 이름|정책 본문|
|:---:|:---:|:---:|:---:|
|#|AdultEducationSubsidies|성인 교육 보조금|성인 교육 보조금은 근로자가 취업한 후에도 (이하생략)|
|#|번역안함|번역|번역|

strings 파일은 

= 오른쪽에 있는 "(여기를 번역)" 쉼표 사이에 부분을 번역해주시면 됩니다. 단

1. :를 임의로 삭제하지 마십시오.
2. (<>) 또는 <>를 번역하지 마십시오. 단 문법에 맞추기 위하여 위치를 변경할 수 있습니다.


예시)

![캡처](https://user-images.githubusercontent.com/30786081/111015327-806b4900-83eb-11eb-9e49-f1f78a69e754.JPG)


  
# 번역하는 방법
  
  1. 번역하시고 싶으신 파일을 선택합니다.
  2. 파일에 들어가신 다음 연필 이모티콘에 edit this file을 누릅니다.
  3. 번역 규칙을 참고하여 번역 혹은 검수하여 내용을 수정합니다.
  4. **@@중요@@** Create pull request를 누릅니다.
  5. 관리자가 확인 후에 해당 내용을 등재할 것입니다.


# 기타
  물어보고 싶으신 내용이 있으시면 창작마당 페이지에 댓글을 작성하거나 Issues 에 issue를 새로 여는 등 언제든지 질문주십시오. 만약 디스코드가 필요하다면 디스코드 서버를 만들겠습니다.
  



