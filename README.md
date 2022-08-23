# 이미지 이름 짓는 규칙

## Default

1. 이미지 이름은 모두 소문자로 입력한다.
2. 단어 사이에 연결은 \_(언더바)로 연결한다.
3. `포맷_역할_상세_옵션` 형식으로 이름을 생성하고 세부 규칙이 필요할 수 있고 생략도 가능하다.

ex) `icon_twitter_mini.svg`, `image_dashbord_wallet.image`

- 포맷: `icon` : svg 이미지, `image`: png 이미지.
- 역할: 주요 역할
- 상세: 역할을 보조하는 상세 설명
- 옵션: `mini`, `dark`, `circle`, `light` 등 옵션을 설명하는 단어(size 포함)

## Chain

- `포맷_체인이름_옵션` 형태로 사용
- ex) `image_celo_color.png`, `image_klaytn.png`

## Protocol

- `포맷_프로토콜이름_옵션` 형태로 사용
- ex) `image_kronos_dao.png`, `image_klay_fi.png`

## Token

- `포맷_토큰심볼_토큰주소` 형태로 사용
- 같은 심볼의 스캠 토큰이 많아 컨트랙트 주소도 추가함
- 체인의 코인은 주소를 `0x0000000000000000000000000000000000000000` 으로 사용함
- ex) `image_kdai_0x5c74070fdea071359b86082bd9f9b3deaafbe32b.png`, `image_kokoa_0xb15183d0d4d5e86ba702ce9bb7b633376e7db29f.png`
