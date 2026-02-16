```cpp
#include <string>
#include <vector>
#include <map>

namespace theshydubii {
class Profile {
public:
    auto getCurrentWorkplace() const -> std::string {
        return "A student, learning and building a portfolio.";
    }

    auto getToolbox() const -> std::vector<std::string> {
        return {"C", "C++", "C#", "Python", "Rust"};
    }

    auto getFocusAreas() const -> std::vector<std::string> {
        return {"C-family engineering", "Data workflows", "Gameplay tooling"};
    }

    auto getGameEngines() const -> std::vector<std::string> {
        return {"Unity", "Unreal Engine", "Godot"};
    }

    auto getContact() const -> std::map<std::string, std::string> {
        return {
            {"Email", "theshydubii@gmail.com"},
            {"X", "x.com/theshydubii"}
        };
    }
};
}
```
