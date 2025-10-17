# scary-stories
Exercise for the "Software Engineering and DevOps" course


# Roles

```java
// 🧙‍♀️ Senior Developer
Senior senior = new Senior("Andjelina");

// 🧪 QA Department
QA qa = new QA("Vladimir");

// 👶 Junior Development Squad
Junior[] juniors = new Junior[]{
    new Junior("Mariya"),
    new Junior("Mehmed"),
    new Junior("Solenkoff")
};

// 🚀 Project Initialization
Team team = new Team(qa, juniors, senior);
team.startSprint();

// ☕ Daily Standup Logic
for (Junior j : juniors) {
    j.report("Accidentally broke it... again.");
    j.assignTask("Fix it before Vladimir finds out.");
}

qa.verifyBuild();
senior.reviewPullRequests();
System.out.println("✅ All bugs successfully rebranded as features!");
