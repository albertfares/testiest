# Bootcamp: B1 Grading Report (SCIPER 355539)

## Points Breakdown

| **Task**                                                 | **Points Awarded**                             | **Feedback**                                  |
| -------------------------------------------------------- | ---------------------------------------------- | --------------------------------------------- |
| **Belt Level**                                           | **Black🥋⚫**         | Fantastic! You've demonstrated true mastery.                |
| **Public Tests**                                         | 27.5 out of 27.5 points | [See Details](#public-tests)                 |
| **Staff Tests**                                          | 5 out of 5 points | [See Details](#staff-tests)                  |
| **User Stories**                                         | 8.25 points (avg: 5/5) | [See Details](#user-stories)                 |
| **Commit Messages**                                      | 8.88 points (avg: 4.8/5) | [See Details](#commit-messages)              |
| **Total score**                                          | **49.63 points**         |                                               |

---

## Final Score

- **Grade:** 5.96/6

---

## Notes

#### Grading Overview

The B1 grade will be calculated once all components are evaluated.

#### Belt Level and Scoring Details:

- **Belt Level Achieved**: Black Belt
- **Public Tests**: 35/35 passed (100.0%) = 27.5 points
- **Staff Tests**: 11/11 passed (100.0%) = 5 points
- **User Stories**: 5/5 average (2 stories) = 8.25 points
- **Commit Messages**: 4.8/5 average (5 commits) = 8.88 points
- **Total Score**: 49.63 points

#### Scoring Method:
Points are awarded based on your belt level. Test points use difficulty weighting: 
`points = (difficulty/sum_of_difficulties_in_suite) × max_points_for_suite`

---

<a name="public-tests"></a>
<details>
  <summary><strong>Public Tests (Click to expand)</strong></summary>

| **Test Name** | **Result** | **Points** |
| ------------- | ---------- | ---------- |
| NavigationB1Test.bottomNavigationIsDisplayedForMap | ✅ passed | 0.14 |
| NavigationB1Test.bottomNavigationIsDisplayedForOverview | ✅ passed | 0.14 |
| NavigationB1Test.bottomNavigationNotDisplayedForAddToDo | ✅ passed | 0.21 |
| NavigationB1Test.canNavigateBackToOverviewFromAddToDo | ✅ passed | 0.29 |
| NavigationB1Test.canNavigateBetweenTabs | ✅ passed | 0.36 |
| NavigationB1Test.canNavigateToAddToDo | ✅ passed | 0.14 |
| NavigationB1Test.canNavigateToMap | ✅ passed | 0.21 |
| NavigationB1Test.canNavigateToMapAndBackToOverview | ✅ passed | 0.21 |
| NavigationB1Test.navigationStartsOnOverviewTab | ✅ passed | 0.14 |
| NavigationB1Test.tabsAreClickable | ✅ passed | 0.14 |
| NavigationB1Test.testTagsAreCorrectlySet | ✅ passed | 0.07 |
| NavigationB1Test.topBarTitleIsCorrectForAddToDo | ✅ passed | 0.14 |
| NavigationB1Test.topBarTitleIsCorrectForMap | ✅ passed | 0.14 |
| NavigationB1Test.topBarTitleIsCorrectForOverview | ✅ passed | 0.14 |
| GreetingScreenTest.clickIsRequiredToUpdateDisplay | ✅ passed | 1.92 |
| GreetingScreenTest.displayCorrectlyUpdates | ✅ passed | 1.54 |
| GreetingScreenTest.displayHasCorrectDefaultValue | ✅ passed | 0.38 |
| GreetingScreenTest.doNotGreetEmptyName | ✅ passed | 0.77 |
| GreetingScreenTest.testTagsAreCorrectlySet | ✅ passed | 0.38 |
| OverviewScreenB1Test.canScrollOnTheTodoList | ✅ passed | 3.41 |
| OverviewScreenB1Test.dueDateIsCorrectlyFormatted | ✅ passed | 2.05 |
| OverviewScreenB1Test.testTagsCorrectlySetWhenListIsEmpty | ✅ passed | 0.68 |
| OverviewScreenB1Test.testTagsCorrectlySetWhenListIsNotEmpty | ✅ passed | 0.68 |
| OverviewScreenB1Test.todoListDisplaysAssigneeName | ✅ passed | 1.36 |
| OverviewScreenB1Test.todoListDisplaysDueDate | ✅ passed | 2.05 |
| OverviewScreenB1Test.todoListDisplaysExistingTodos | ✅ passed | 1.36 |
| OverviewScreenB1Test.todoListDisplaysStatus | ✅ passed | 2.05 |
| OverviewScreenB1Test.todoListDisplaysTaskName | ✅ passed | 1.36 |
| ToDosRepositoryLocalTest.addToDo_succeeds | ✅ passed | 0.59 |
| ToDosRepositoryLocalTest.correcltyGeneratesNewUID | ✅ passed | 0.29 |
| ToDosRepositoryLocalTest.deleteToDoById_callsOnFailure_whenToDoNotFound | ✅ passed | 0.88 |
| ToDosRepositoryLocalTest.deleteToDoById_callsOnSuccess | ✅ passed | 0.59 |
| ToDosRepositoryLocalTest.deleteToDoById_deletesTheCorrectToDo | ✅ passed | 0.88 |
| ToDosRepositoryLocalTest.updateToDo_failsWhenToDoNotFound | ✅ passed | 0.88 |
| ToDosRepositoryLocalTest.updateToDo_succeeds | ✅ passed | 0.88 |
| **Total Public Tests** | 35/35 passed (100.0%) |

</details>

---

<a name="staff-tests"></a>
<details>
  <summary><strong>Staff Tests (Click to expand)</strong></summary>

| **Test Name** | **Result** | **Points** |
| ------------- | ---------- | ---------- |
| OverviewScreenB1StaffTest.dueDateIsCorrectlyFormattedForDay | ✅ passed | 0.29 |
| OverviewScreenB1StaffTest.dueDateIsCorrectlyFormattedForMonth | ✅ passed | 0.29 |
| OverviewScreenB1StaffTest.dueDateIsCorrectlyFormattedForYear | ✅ passed | 0.29 |
| OverviewScreenB1StaffTest.todoListIsLazy | ✅ passed | 0.14 |
| NavigationB1StaffTest.canExitTheAppFromMapWithTwoTapOnBackButton | ✅ passed | 0.43 |
| NavigationB1StaffTest.clickOnCurrentTabDoesNotRecompose | ✅ passed | 0.71 |
| NavigationB1StaffTest.navigateBackFromAddToDoRestoresState | ✅ passed | 0.71 |
| NavigationB1StaffTest.navigateBackOnOverviewTabExitsApp | ✅ passed | 0.43 |
| NavigationB1StaffTest.navigateBetweenTabsDoNotRestoreState | ✅ passed | 0.57 |
| NavigationB1StaffTest.navigateBetweenTabsDoNotStack | ✅ passed | 0.57 |
| NavigationB1StaffTest.navigateToMapFromMapAndPressBackGoesToOverview | ✅ passed | 0.57 |
| **Total Staff Tests** | 11/11 passed (100.0%) |

You can find the staff test descriptions [here](https://github.com/swent-epfl/public/blob/main/bootcamp/docs/staff-test-descriptions.md).

</details>

---

<a name="user-stories"></a>
<details>
  <summary><strong>User Stories (Click to expand)</strong></summary>

| **User Stories** | **Score [0-5]** | **Comments** |
| ---------------- | --------------- | ------------ |
| 1. As a user, I want to assign priority levels to my ToDos, so that I can organize my work and focus on the most important tasks first. | 5 | This user story is clear, relevant, and well-scoped, effectively addressing the need for task prioritization in the ToDo app. Great job! |
| 2. As a user, I want to categorize my ToDos using tags, so that I can organize and filter my task list effectively. | 5 | Great job! The story is clear, relevant, and appropriately scoped, making it easy to understand the value of tagging for task organization. |
| **Average User Stories Score** | 5 / 5 | |

</details>

---

<a name="commit-messages"></a>
<details>
  <summary><strong>Commit messages (Click to expand)</strong></summary>

| **Commit messages** | **Score [0-5]** | **Comments** |
| ------------------- | --------------- | ------------ |
| refactor(todo): improve ToDosRepositoryLocal implementation<br><br>This commit refactors the local ToDo repository to make it more robust and efficient.<br>  - getNewUid: Ensures the generated UID is always unique by checking against the existing list of todos.<br>  - addTodo: Adds a check to prevent adding a todo with a UID that already exists, throwing an IllegalArgumentException.<br>  - editTodo: Improves efficiency by finding the index of the todo and replacing it in-place, rather than deleting and re-adding. This also preserves the order of the items.<br>  - deleteTodo: Adds an exception throw if the item to be removed is not found in the list, making the operation safer. | 5 | The commit message has lines in the body that exceed 72 characters, which should be split into shorter lines to enhance readability. |
| docs(stories): add new user stories<br><br>This commit adds two new user stories to the project requirements in `userStories.txt`. | 4 | The commit message is clear and detailed but could benefit from improved structure or wording. The body provides meaningful information and valuable context, but it contains lines that exceed 72 characters, which should be split into shorter lines for better readability. |
| feat(nav): implement app navigation structure<br><br>This commit sets up the primary navigation flow for the application using Jetpack Compose Navigation.<br><br>It introduces a Scaffold to provide a consistent layout with:<br>- A TopAppBar that displays the title of the current screen.<br>- A BottomNavigationBar to switch between the "Overview" and "Map" main screens.<br>- A FloatingActionButton on the Overview screen to navigate to the "AddTodoScreen".<br>- A NavHost that defines the navigation graph between screens. | 5 | The commit message body contains lines that exceed 72 characters, which should be split into shorter lines to improve readability. |
| feat(overview): implement todo list screen<br><br>This commit introduces the overview screen which displays a list of tasks from an in-memory repository.<br><br>The implementation follows the MVVM architecture:<br>- Model: `ToDosRepositoryLocal` manages the list of todos.<br>- ViewModel: `OverviewViewModel` prepares and exposes the list of todos as a StateFlow for the UI.<br>- View: `OverviewScreen` uses a LazyColumn to efficiently display the tasks, with each item rendered in a Card. | 5 | The commit message contains lines in the body that exceed the recommended 72-character limit, which can hinder readability. It's important to split long lines into shorter ones to enhance clarity. |
| feat(greeting): implement initial greeting app<br><br>This commit introduces the first feature of the bootcamp: a simple greeting application.<br><br>The implementation uses Jetpack Compose to create a user interface with the following components:<br>  - A text field for the user to enter their name.<br>  - A button to submit the name.<br>  - A text display that shows a personalized greeting message. | 5 | The commit message has lines in the body that exceed 72 characters, which should be split into shorter lines for better readability. |
| **Average commit messages score** | 4.8 / 5 | |

</details>

