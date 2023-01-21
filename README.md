```cpp
namespace invertime;

class About : public Me {

    private:
        map<string, string> CurrentWorkplace = {
                { 'Place', 'High School' },
                { 'Position', 'Student' }
            };

        string dailyKnowledge = {
            "Html", 
            "CSS",
            "JavaScript",
            "Php",
            "Laravel",
            "Vuejs",
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