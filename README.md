# 소개
Unity6를 기반으로 하나의 프로젝트 내에 각 팀 별로 미니 게임을 제작한 프로젝트입니다.<br/>
해당 프로젝트 내에서 턴제 RPG 게임인 DSG의 개발을 담당했습니다.

+ 개발 환경 : Unity 6000.0.62f1, Git(Fork)
+ 플랫폼 : PC
+ 개발 인원 : 3명


# 담당 업무

## 1. 팀 편성 시스템
<details>
<summary><b>보기</b></summary>

<details>
<summary><b>DeckStrategyStage(Model)</b></summary>
https://github.com/SeongJeGyeong/ProjectLUP_DSG/blob/809d354361254fc854b9db535ad64d49ff23e8b8/Assets/2_Scripts/-Stage/DSG/DeckStrategyStage.cs#L1-L294
</details>
<details>
<summary><b>FormationPresenter(Presenter)</b></summary>
https://github.com/SeongJeGyeong/ProjectLUP_DSG/blob/809d354361254fc854b9db535ad64d49ff23e8b8/Assets/2_Scripts/Games/DSG/0_System/FormationPresenter.cs#L1-L215
</details>
<details>
<summary><b>FormationView</b></summary>
https://github.com/SeongJeGyeong/ProjectLUP_DSG/blob/809d354361254fc854b9db535ad64d49ff23e8b8/Assets/2_Scripts/Games/DSG/0_System/FormationView.cs#L1-L121
</details>
<details>
<summary><b>TeamSelectButton(View)</b></summary>
https://github.com/SeongJeGyeong/ProjectLUP_DSG/blob/0bb4cfc33afb87c7eca8f1cc7cbc955c57c79c81/Assets/2_Scripts/Games/DSG/1_UI/DeckEditUI/TeamSelectButton.cs#L1-L48
</details>
<details>
<summary><b>CharactersList(View)</b></summary>
https://github.com/SeongJeGyeong/ProjectLUP_DSG/blob/809d354361254fc854b9db535ad64d49ff23e8b8/Assets/2_Scripts/Games/DSG/1_UI/DeckEditUI/CharactersList.cs#L1-L100
</details>
<details>
<summary><b>CharacterFilterPanel(View)</b></summary>
https://github.com/SeongJeGyeong/ProjectLUP_DSG/blob/809d354361254fc854b9db535ad64d49ff23e8b8/Assets/2_Scripts/Games/DSG/1_UI/DeckEditUI/CharacterFilterPanel.cs#L1-L95
</details>  
<details>
<summary><b>오브젝트 풀</b></summary>

</details>
</details>

## 2. 캐릭터 UI
<details>
<summary><b>보기</b></summary>
<details>
<summary><b>CharacterBattleUI</b></summary>
https://github.com/SeongJeGyeong/ProjectLUP_DSG/blob/0bb4cfc33afb87c7eca8f1cc7cbc955c57c79c81/Assets/2_Scripts/Games/DSG/1_UI/BattleUI/CharacterBattleUI.cs#L1-L204
</details>
</details>

## 3. 셰이더
<details>
<summary><b>보기</b></summary>
<details>
<summary><b>스킬 게이지 최대치일 경우 셰이더 적용</b></summary>
https://github.com/SeongJeGyeong/ProjectLUP_DSG/blob/0bb4cfc33afb87c7eca8f1cc7cbc955c57c79c81/Assets/2_Scripts/Games/DSG/1_UI/BattleUI/CharacterBattleUI.cs#L59-L86
https://github.com/SeongJeGyeong/ProjectLUP_DSG/blob/0bb4cfc33afb87c7eca8f1cc7cbc955c57c79c81/Assets/2_Scripts/Games/DSG/1_UI/BattleUI/CharacterBattleUI.cs#L108-L116
</details>
<details>
<summary><b>Dither 셰이더를 통한 캐릭터 반투명 처리</b></summary>
https://github.com/SeongJeGyeong/ProjectLUP_DSG/blob/0bb4cfc33afb87c7eca8f1cc7cbc955c57c79c81/Assets/2_Scripts/Games/DSG/2_Character/Components/ObjectFader.cs#L1-L51
</details>
</details>

## 4. DoTween을 활용한 카메라 연출
<details>
<summary><b>보기</b></summary>
https://github.com/SeongJeGyeong/ProjectLUP_DSG/blob/0bb4cfc33afb87c7eca8f1cc7cbc955c57c79c81/Assets/2_Scripts/Games/DSG/0_System/BattleCameraDirector.cs#L1-L90
</details>
