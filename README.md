# SFSD\\
## Description de la contribution pour chaque membre : <br>
1-Nacer Bey Abderrahmane Zakaria : <br>
## Controller

- **DashboardController**
  - `ShowPriorityNotification()`
  - `SetCurrentId(int userId)`
  - `loadUserScoreAndRank()`
  - `StopAllReminders()`
  - `loadTaskFromDatabase()`
  - `handleLeaderboard(ActionEvent event)`
  - `handleAccueilClick(ActionEvent event)`
  - `SetUsername(String username)`
  - **Edited on:**
    - `populateFilters()`
    - `applyFilters()`
    - `handleSearchFilter(KeyEvent event)`

- **LeaderboardController**
  - All methods

- **SignInController**
  - `goToDashboard(int userId, String username)`

- **TableauxController**
  - `handleUncompletedTasks()`
  - `showUncompletedTask(List<Task> task, String difficultCategory)`
  - `showAlert(String message)`

---

## Model

- **LeaderboardEntry**
- **TaskDAO**
  - `getUncompletedTaskByCategory()`
  - `getUserScoreAndRank(int userId)`
- **User**
  - Constructors
  - `calculateScore()`
- **UserDAO**
  - `getLeaderboardUsers()`
  - **Edited on:** `getUserById(int id)`

---

## View

- `Leaderboard2.fxml`
- **Edited on:** `Dashboard.fxml`

 
        
