pipeline {
         agent any
          stages{
                    stage ("version control system") {
                              git url: https://github.com/abdsamadf/battleship-style-game.git
                    }
                    stage ("compile the code") {
                              sh "cd Snake-Game && javac DotCom.java && javac DotComBust.java && javac GameHelper.java"
                    }
                    stage ("run") {
                              sh "java DotComBust"
                    }
          }
}
