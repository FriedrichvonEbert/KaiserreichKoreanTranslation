
# Kaiserreich 한국어 번역 공지사항
## [Kaiserreich 한국어 번역](https://steamcommunity.com/sharedfiles/filedetails/?id=2098453801)은 공개 번역으로 진행됩니다.
- 번역팀 디스코드 주소 : https://discord.gg/JwxDFmRv6a
### [0.17 패치노트](https://www.reddit.com/r/Kaiserreich/comments/mswyzz/kaiserreich_017_springtime_for_kaiser/)
- 21.04.19 기준 한국어 번역의 0.17 호환 작업이 완료되었습니다.
***

## 번역 방법 
- 21년 4월부로 앞으로의 번역 작업은 유로파카페와 같이 [Pontoon](https://translate.readingsnail.pe.kr/ko/)에서 진행됩니다.
### 안내 및 경고
- 카이저라이히는 아직 BETA 단계이므로 계속 문법/단어 수정이 이뤄지고 있습니다. 번역하려는데 문장이 이상하다고 생각하신다면 재량에 따라 의역하셔도 됩니다.
- **[단어사전](단어사전.md)** 을 지켜주시며 본문 수정 부탁드립니다.
- 한번도 번역되지 않은 지명, 인명들은 적당히 발음나는 대로 적어주시면 됩니다.
  - 필요시 [한글라이즈](https://hangulize.org)나 [한어병음/일문가나 한글표기 변환 도구](https://herba.kr/boncho/tool.php), [키릴문자-라틴어 변환 도구](https://www.lexilogos.com/keyboard/russian_conversion.htm), 그리고 `Issue`탭을 활용해 주세요.
- 이 외에 번역과 관련된 토론은 상단 `Issues` 탭에 올려주시면 답해드리겠습니다.
- **번역기를 사용한 문장을 그대로 붙여넣지 마십시오. 1차 경고 이후에 지속될 경우, Block 등의 조치를 취하겠습니다.**
- **이미 [Pull requests](https://github.com/FriedrichvonEbert/KaiserreichKoreanTranslation/pulls)에 대기 중인 파일을 번역하셨다면, 얼마나 더 하시든 관리자가 가장 최근에 수락한 것만 적용됩니다. `Pull requests`에서 해당 파일이 사라지기 이전까지 다른 파일을 작업해주세요.**
***
### 번역 규칙
**1. 번역 이전**
  - 반드시 `localisation` 폴더의 파일만 번역합니다.
  - 번역 전 상단의 `Pull requests` 탭을 눌러, 번역할 부분이 이미 다른 사람에 의해 번역 요청이 된 부분인지 확인해 주세요.
    
**2. 번역 도중**
  - 반드시 큰따옴표(`""`)안의 내용만 번역합니다.
  - 대괄호(`[]`)나 달러 기호(`$$`) 사이의 내용은 번역하지 않습니다.
  - 파운드 기호(`£`) 다음에 오는 내용은 게임에서 아이콘으로 구현되는 부분으로 번역하지 않습니다.
  - 개행 기호(`\n`)는 줄바꿈 기호로써 번역하지 않습니다.
  - 부분 기호(`§§!`) 사이의 첫 대문자 알파벳은 글자 색상을 지정하는 것으로 번역하지 않습니다.
  - 어떤 경우에도 파일 첫 줄의 `l_english:` 앞에 있는 붉은 점을 삭제하면 안됩니다.
    - 실수로 삭제한 채 `Pull requests`요청을 했다면, `Issues`탭 혹은 해당 요청에 코멘트를 적어주세요.
  - 문장 내부에 사용된 큰따옴표(`""`)를 삭제하거나, 작은따옴표(`''`)같은 다른 기호로 대체하면 안됩니다.
```
번역 예시:
  KR_and_FR:0 "§YKaiserreich§! and §YFuhrerreich§!"
  KR_and_FR:0 "§Y카이저라이히§!(와)과 §Y퓌러라이히§!"
  camel_corps_tech_effect:0 "Enables §HCamel Corps§!\n§HCavalry\n    Desert§!\n      Attack: §G+15%§!\n"
  camel_corps_tech_effect:0 "§H낙타 부대§! 활성화\n§H기병\n    사막§!\n      공격: §G+15%§!\n"
```

**3. 번역 이후**
  - 번역은 관리자가 `Pull request`탭에 올라온 내용을 수락한 다음 반영될 것입니다.
***

## 번역시 도움되는 페이지
 파란 단어를 클릭하면 해당 사이트로 넘어갑니다.
- **자료검색** - 모르는 단어가 중간에 나오면 최소한 한번은 검색하고 진행해주세요.
  - [카이저라이히 번역팀 단어사전](단어사전.md)
  - [위키백과(위키피디아) 한국어판](https://ko.wikipedia.org)
  - [위키백과(위키피디아) 영문판](https://en.wikipedia.org) 
    - 영문 위키에서 검색 후, 좌측란의 `Language`를 통해 한국어판에선 어떻게 표기되었는지 확인할 수 있습니다.
  - [네이버](https://www.naver.com)
  - [구글](https://www.google.com)
- **번역기** - 오로지 **참조**로만 사용하십시오. 재차 경고합니다.
  - [파파고](https://papago.naver.com/)
  - [구글 번역](https://translate.google.co.kr/)
- **원문 한글 표기와 문장교정**
  - [한글라이즈](https://hangulize.org) - 각 언어에 맞는 글자를 넣어야 정상적으로 출력됩니다.
  - [한어병음/일문가나 한글표기 변환 도구](https://herba.kr/boncho/tool.php) - 중국어를 로마자로 표기한 것을 넣으면 변환이 됩니다.
  - [키릴문자-라틴어 변환 도구](https://www.lexilogos.com/keyboard/russian_conversion.htm) - 영문으로 적힌 러시아어를 변환하는데 도움이 됩니다. 그 역에도 도움이 됩니다.
  - [한국어 맞춤법/문법 검사기](http://speller.cs.pusan.ac.kr/) - 번역 후에 어색한 느낌이 든다면 사용해보세요. 강한 규칙 적용을 권장드립니다.
***

## 번역팀 자매 프로젝트   
아래 번역에도 많은 기여를 부탁드립니다.
- RedFlood 한국어 번역
  - [Red-Flood-Korean](https://github.com/Edietchek/Red-Flood-Korean)
- Road to 56 한국어 번역
  - [Road-to-56-Korean](https://github.com/codmw123/Road-to-56-Korean)
- The New Order 한국어 번역
  - [TheNewOrderKoreanTranslation](https://github.com/FriedrichvonEbert/TheNewOrderKoreanTranslation)
