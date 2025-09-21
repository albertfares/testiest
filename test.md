# Bootcamp: B1 Grading Report (SCIPER 303958)

## Points Breakdown

| **Task**                                                 | **Points Awarded**                             | **Feedback**                                  |
| -------------------------------------------------------- | ---------------------------------------------- | --------------------------------------------- |
| **Belt Level**                                           | **Blue🥋🔵**         | Excellent work! You're showing advanced skills.                |
| **Public Tests**                                         | 27.5 out of 27.5 points | [See Details](#public-tests)                 |
| **Staff Tests**                                          | 4.43 out of 5 points | [See Details](#staff-tests)                  |
| **User Stories**                                         | 6.25 points | [See Details](#user-stories)                 |
| **Commit Messages**                                      | 6.25 points | [See Details](#commit-messages)              |
| **Total score**                                          | **44.43 points**         | **Grade:** 5.44/6 |

---

## Scoring Details

- **Belt Level Achieved**: Blue Belt
- **Public Tests**: 35/35 passed (100.0%) = 27.5 points
- **Staff Tests**: 10/11 passed (90.9%) = 4.43 points
- **User Stories**: 5/5 average (2 stories) = 6.25 points
- **Commit Messages**: 5/5 average (4/6 commits used for grading) = 6.25 points
- **Total Score**: 44.43 points

> [!IMPORTANT]  
> Your commit messages and user stories were evaluated using AI. To account for potential errors, we excluded your **2** lowest-scoring commit messages from the final grade calculation. However, you can see the scores and feedback for all your commits in the detailed breakdown below. If you believe the evaluation was unfair and wish to request manual review for all your commit messages and user stories, please open an issue in your GitHub repository with the title "Manual grading request for B1". Note that manual review will consider all commit messages, which may result in a different (potentially lower) grade.

#### Belt Criteria:

- **White Belt** (max 30 points): You committed something to the repository before the deadline
- **Yellow Belt** (max 35 points): In addition to White,
  - Pass all the public tests for Greeting and Todo List
  - Your commit messages are acceptable
  - The two user stories are acceptable
- **Green Belt** (max 40 points): In addition to Yellow,
  - Pass all the public tests for Navigation
  - Your commit messages are good
  - The two user stories are good
- **Blue Belt** (max 45 points): In addition to Green,
  - Pass all the staff tests for TodoList
  - Your commit messages are good
  - The two user stories are good
- **Black Belt** (max 50 points): In addition to Blue,
  - Pass all the staff tests for Navigation
  - Your commit messages are perfect
  - The two user stories are perfect

> [!NOTE]
> **Acceptable**: Average grade ≥ 2.5/5  
> **Good**: Average grade ≥ 3.5/5  
> **Perfect**: Average grade ≥ 4.5/5

**Test Points**: Points are computed depending on the test's difficulty.

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
| **Total Public Tests** | 35/35 passed (100.0%) | 27.5 |

</details>

---

<a name="staff-tests"></a>
<details>
  <summary><strong>Staff Tests (Click to expand)</strong></summary>

| **Test Name** | **Result** | **Points** |
| ------------- | ---------- | ---------- |
| <a href="#" title="Checks that the due date displays the day component with two digits (e.g., &quot;02&quot; instead of &quot;2&quot;) in the &quot;dd/MM/yyyy&quot; format.">OverviewScreenB1StaffTest.dueDateIsCorrectlyFormattedForDay</a> | ✅ passed | 0.29 |
| <a href="#" title="Checks that the due date displays the month component with two digits (e.g., &quot;09&quot; instead of &quot;9&quot;) in the &quot;dd/MM/yyyy&quot; format.">OverviewScreenB1StaffTest.dueDateIsCorrectlyFormattedForMonth</a> | ✅ passed | 0.29 |
| <a href="#" title="Checks that the due date displays the year component with four digits (e.g., &quot;2025&quot; instead of &quot;25&quot;) in the &quot;dd/MM/yyyy&quot; format.">OverviewScreenB1StaffTest.dueDateIsCorrectlyFormattedForYear</a> | ✅ passed | 0.29 |
| <a href="#" title="Checks that the todo list is lazy loaded by creating 100 todos and confirming that the last one is not displayed without scrolling.">OverviewScreenB1StaffTest.todoListIsLazy</a> | ✅ passed | 0.14 |
| <a href="#" title="Checks that pressing the back button twice from the Map tab first returns to Overview and then exits the app.">NavigationB1StaffTest.canExitTheAppFromMapWithTwoTapOnBackButton</a> | ✅ passed | 0.43 |
| <a href="#" title="Checks that clicking the already-selected Overview tab does not recompose or reset the screen state (e.g., scroll position).">NavigationB1StaffTest.clickOnCurrentTabDoesNotRecompose</a> | ✅ passed | 0.71 |
| <a href="#" title="Checks that navigating to AddToDo and then back to Overview restores the previous Overview state, including scroll position.">NavigationB1StaffTest.navigateBackFromAddToDoRestoresState</a> | ✅ passed | 0.71 |
| <a href="#" title="Checks that pressing the system back button while on the Overview tab closes the app.">NavigationB1StaffTest.navigateBackOnOverviewTabExitsApp</a> | ✅ passed | 0.43 |
| <a href="#" title="Checks that switching between Overview and Map tabs resets the Overview state (e.g., scroll position is lost), rather than restoring it.">NavigationB1StaffTest.navigateBetweenTabsDoNotRestoreState</a> | ❌ failed | 0 |
| <a href="#" title="Checks that repeatedly switching between Overview and Map tabs does not create multiple stacked instances of the same screen, and pressing back exits the app.">NavigationB1StaffTest.navigateBetweenTabsDoNotStack</a> | ✅ passed | 0.57 |
| <a href="#" title="Checks that tapping the Map tab twice keeps the user on the Map screen, and pressing back correctly returns to Overview instead of stacking Map.">NavigationB1StaffTest.navigateToMapFromMapAndPressBackGoesToOverview</a> | ✅ passed | 0.57 |
| **Total Staff Tests** | 10/11 passed (90.9%) | 4.43 |

*Hover over test names above to see detailed descriptions. Note: This feature works best when viewing the report in a desktop web browser.*

</details>

---

<a name="user-stories"></a>
<details>
  <summary><strong>User Stories (Click to expand)</strong></summary>

| **User Stories** | **Score [0-5]** | **Comments** |
| ---------------- | --------------- | ------------ |
| 1. As a user, I want to set reminders for my ToDos, so that I am notified when a task is due. | 5 | Great job! The story is clear, relevant, and perfectly scoped for the ToDo app, ensuring users can effectively manage their tasks. |
| 2. As a user, I want to mark my ToDos as completed or archived, so that I can keep my list organized and focus on pending tasks. | 5 | This user story is clear, relevant, and well-scoped, effectively addressing the need for organization and focus within the ToDo app. Great job! |
| **Average User Stories Score** | 5 / 5 | |

</details>

---

<a name="commit-messages"></a>
<details>
  <summary><strong>Commit messages (Click to expand)</strong></summary>

| **Commit messages** | **Score [0-5]** | **Comments** |
| ------------------- | --------------- | ------------ |
| chore: update actualTimeB1.csv with time spent on each step | 5 | The commit message is perfect and adheres fully to conventional commit standards. No improvements are needed. |
| feat: add two new user stories to extend ToDo app functionality | 5 | The commit message is well-crafted and follows conventional commit standards effectively. It clearly describes the feature addition with a concise summary. There are no issues to address, and it demonstrates good practice in commit message writing. |
| chore(tests): update CI tests for step B1.5 | 5 | The commit message is perfect and adheres fully to conventional commit standards. No issues need to be addressed. |
| feat(B1.4): implement navigation with Overview, Map, and AddToDo screens<br><br>- Updated MainActivity to host BootcampApp with Scaffold.<br>- Added MapScreen and AddTodoScreen composables for navigation targets.<br>- Integrated navigation to switch between Overview, Map, and AddToDo screens.<br>- Wired floating action button on OverviewScreen to navigate to AddToDoScreen.<br>- Ensured correct display of top bar titles and bottom navigation visibility per screen. | 4.5 | The commit message description is too long and should be concise, ideally under 50 characters. The body contains lines that exceed 72 characters and should be split into shorter lines for better readability. |
| feat(B1.3): implement OverviewScreen and ToDo state management<br><br>- Added OverviewScreen composable with LazyColumn to display the list of ToDos.<br>- Created TodoListItem reusable composable for displaying individual ToDos.<br>- Integrated OverviewViewModel to manage ToDo state using a repository.<br>- Added FloatingActionButton for creating new ToDos.<br>- Configured ToDosRepositoryProvider with a local repository for local preview | 5 | The commit message is perfect and adheres fully to conventional commit standards. No improvements are needed. |
| feat(B1.2): add GreetingScreen composable for initial Android setup<br>- Added a GreetingScreen composable that prompts the user to enter their name.<br>- Includes a validate button that displays the entered name on the screen on click. | 5 | The commit message is perfect and adheres fully to conventional commit standards. No improvements are needed. |
| **Average commit messages score** | 5 / 5 | |

</details>

