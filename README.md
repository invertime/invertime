```cpp
namespace invertime;

class About : public Me {

    private:
        map<string, string> CurrentWorkplace = {
                { 'Place', 'Higher school preparatory classes' },
                { 'Position', 'Student' }
            };

        string randomKnowledge = {
            "Html", 
            "CSS",
            "JavaScript",
            "Typescript",
            "Php",
            "Vuejs",
            "C",
            "Ocaml",
            "C++",
            "CyberSecurity"
        }

    public:

        map<string, string> getCurrentWorkplace(){            
            return CurrentWorkplace
        };

        string getDailyKnowledge(){
            return randomKnowledge
        }

        string getFuturGoal(){
            return "To get a job in cybersecurity"
        }
}
```
