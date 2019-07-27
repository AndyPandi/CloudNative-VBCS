# Part 2: User Interface

## 소개
이번 실습에서는 front-end UI를 만들고 UI 컴포넌트로 Business Object의 데이터를 bind 할 것 입니다. 그리고 수정 화면과 삭제 기능 또한 구현할 것 입니다.

### Steps
----
#### 1. Header 추가
> 다음 두 단계에서는 이 어플리케이션의 메인페이지를 생성합니다.

![alt text](../resources/images/ui/29.png) 

![alt text](../resources/images/ui/30-new.png)

![alt text](../resources/images/ui/31-new.png)

> 이제 컴포넌트 팔레트에서 header 컴포넌트를 어플리케이션 메인화면의 캔버스로 드래그 앤 드랍하세요.

![alt text](../resources/images/ui/32-new.png)

![alt text](../resources/images/ui/33-new.png)

![alt text](../resources/images/ui/34-new.png)
#### 2. 구분선 추가
> header 와 구분선 을 메인 어플리케이션 페이지에 추가 합니다.

![alt text](../resources/images/ui/35-new.png)

![alt text](../resources/images/ui/36-new.png)

#### 3. Table 추가
> 다음은 사원 데이터를 표시할 Table 컴포넌트를 어플리케이션 메인페이지에 추가합니다. Employee Business Object 에서 데이터를 검색하고 UI 컴포넌트에 binding 하는 방법을 가이드할 예정이니다.

![alt text](../resources/images/ui/37-new.png)

![alt text](../resources/images/ui/38-new.png)

![alt text](../resources/images/ui/39-new.png)

![alt text](../resources/images/ui/40-new.png)

![alt text](../resources/images/ui/41-new.png)

![alt text](../resources/images/ui/43-new.png)

![alt text](../resources/images/ui/44-new.png)

![alt text](../resources/images/ui/44a-new.png)

![alt text](../resources/images/ui/45-new.png)

![alt text](../resources/images/ui/46-new.png)

#### 4. view 조정하기
> 현재 사원 데이터 Table 컴포넌트에 나타나고 있고 이것을 full page view로 볼 수 있도록 하겠습니다. 페이지를 줌인, 줌아웃이 아닌 `Fit`되게 할 수 있습니다. 아래 그림에서 확인할 수 있습니다.

![alt text](../resources/images/ui/47.png "Logo Title Text 1")

![alt text](../resources/images/ui/48.png "Logo Title Text 1")

<!--
#### 5. Adjust Table
Now we have a full view of the table, we most probably want to change the name or the sequence of the table columns. The following steps will guide you how this can be done.

![alt text](../resources/images/ui/49.png "Logo Title Text 1")

![alt text](../resources/images/ui/50.png "Logo Title Text 1")

![alt text](../resources/images/ui/51.png "Logo Title Text 1")

![alt text](../resources/images/ui/52.png "Logo Title Text 1")

![alt text](../resources/images/ui/53.png "Logo Title Text 1")

![alt text](../resources/images/ui/54.png "Logo Title Text 1")

-->

#### 5. Change Picture component in Table
> Now we have a full view of the table, we most probably want to change the way we present the picture. The following steps will guide you how this can be done.

![alt text](../resources/images/ui/AT-1.png)

![alt text](../resources/images/ui/AT-2.png)

![alt text](../resources/images/ui/AT-3.png)

![alt text](../resources/images/ui/AT-4.png)

![alt text](../resources/images/ui/AT-5.png)

![alt text](../resources/images/ui/AT-6.png)

![alt text](../resources/images/ui/AT-7.png)

![alt text](../resources/images/ui/AT-8.png)

![alt text](../resources/images/ui/AT-9.png)

#### 6. Adding actions
> Now you're done with your table, next is adding some actions to the data. The next few steps will guide you on adding a Create Employee function and Edit Employee function. You will notice that VBCS has some nice pre-built quickstarts to help you generating the various pages and linking the navigation.

![alt text](../resources/images/ui/55-new.png)

![alt text](../resources/images/ui/56-new.png)

<!-- remove ![alt text](../resources/images/ui/57.png) -->

![alt text](../resources/images/ui/58-new.png)

![alt text](../resources/images/ui/81.png)

![alt text](../resources/images/ui/59-new.png)

![alt text](../resources/images/ui/60-new.png)

![alt text](../resources/images/ui/61-new.png)

![alt text](../resources/images/ui/62-new.png)

#### 7. Adding Create page
> We have completed creating the `Create Employee` page and we can now test this functionality.

![alt text](../resources/images/ui/63-new.png)

<!-- remove ![alt text](../resources/images/ui/64.png) -->

![alt text](../resources/images/ui/65-new.png)

#### 8. Adding Edit page
> Next section of this lab, we will guide you on how to add a `Edit Employee` function. Before that we need to make sure we are back to out application `main-start` page.

![alt text](../resources/images/ui/66-new.png)

<!-- remove ![alt text](../resources/images/ui/67.png)-->

![alt text](../resources/images/ui/82.png)

![alt text](../resources/images/ui/68-new.png)

![alt text](../resources/images/ui/69-new.png)

![alt text](../resources/images/ui/70-new.png)

![alt text](../resources/images/ui/71-new.png)

![alt text](../resources/images/ui/72-new.png)

![alt text](../resources/images/ui/73-new.png)

![alt text](../resources/images/ui/74-new.png)

![alt text](../resources/images/ui/75-new.png)

<!-- ![alt text](../resources/images/ui/76.png) -->

#### 9. Adding Delete
> Before we move to our next section, we have to navigate back to our `main-start` page. We will guide you through a creation of the `Delete Employee` function.

![alt text](../resources/images/ui/77-new.png)

<!-- remove ![alt text](../resources/images/ui/78.png) -->

![alt text](../resources/images/ui/79-new.png)

![alt text](../resources/images/ui/80-new.png)

#### 10. The results
Now you are ready to test and run your application. Click on the `Play` icon.

![alt text](../resources/images/ui/83.png)

The result of your hard work.

![alt text](../resources/images/ui/84-new.png)
----
### You have completed Part 2 of this lab. Proceed to Part 3.

> [`HOME`](../README.md) | [`PART 1`](PART_1.md) | [`PART 2`](PART_2.md) | [`PART 3`](PART_3.md)
