# SFSD\\
Description de la contribution pour chaque membre : \\
1-Nacer Bey Abderrahmane Zakaria : \\
Controller : \\
-DashboardController
  * ShowPriorityNotification();\\
  * SetCurrentId(Int UserId);\\
  * loadUserScoreAndRank();\\
  * StopAllReminders();\\
  * loadTaskFromDatabase();\\
  * handleLeaderboard(Action Event event);\\
  * handleAccueilClick(Action Event event);\\
  * SetUsername(String Username);\\
  * Edited on:\\
      populateFilters();\\
      applyFilters();\\
      handleSearchFilter(Keyevent event);\\
-LeaderboardController (All methodes)\\
-SignInController\\
  * goToDashboard(Int userId , String username);\\
-TableauxController\\
  * handleUncompletedTasks();\\
  * showUncompletedTask(List<Task> task , String difficultCategory);\\
  * showAlert(String message);\\
Model :\\
-LeaderboardEntry\\
-TaskDAO\\
  * getUncompletedTaskByCategory();\\
  * getUserScoreAndRank(Int userId);\\
-User
  *Constructors;\\
  *calculateScore();\\
-UserDAO\\
  *getLeaderboardUsers();\\
  * Edited on getUserById(Int id);\\
View :\\
-Leaderboard2.fxml\\
-Edited on Dashboard.fxml
 
        
