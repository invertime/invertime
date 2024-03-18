```cpp
namespace invertime;

class About : public Me {

    private:
        map<string, string> CurrentWorkplace = {
                { 'Place', 'Higher school preparatory classes' },
                { 'Position', 'Student' }
            };

        string dailyKnowledge = {
            "Html", 
            "CSS",
            "JavaScript",
            "Php",
            "Laravel",
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
            return dailyKnowledge
        }

        string getFuturGoal(){
            return "To get a job in cybersecurity"
        }
}
```
