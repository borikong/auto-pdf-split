# 영수증 첨부지 별 PDF 쪼개기
![image](https://user-images.githubusercontent.com/32058390/161851154-2d91539b-7131-450c-b55c-11015c3c5058.png)

<동작>
**1. 입력 : PDF, 저장 위치**

![image](https://user-images.githubusercontent.com/32058390/161852509-fda4479a-4a69-4f4e-a4d9-e8777b79fb4f.png)


**2. pdf를 img로 변환**
- folder : 'pdf2img'

![image](https://user-images.githubusercontent.com/32058390/161851362-46ec4783-fbd6-4e82-9ee6-765c73b37f28.png)

**3. 이미지 상단만 cropping**
- folder : 'cropped_image'

![image](https://user-images.githubusercontent.com/32058390/161852060-68434461-bcd9-4f7f-87cf-d1b72d5aad51.png)

**4. ocr 문자인식으로 영수증 시작 페이지 구분, 금액/비목 등 읽어옴**

![image](https://user-images.githubusercontent.com/32058390/161852448-ede3ee4d-6c9a-4731-a954-a7cb2d36faf6.png)

**5. 나눠진 페이지 별로 pdf 저장, 파일명 라벨링**

![image](https://user-images.githubusercontent.com/32058390/161852625-97c28545-c200-48c3-855a-5a27c98512e8.png)
