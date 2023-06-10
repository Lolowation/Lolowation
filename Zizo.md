- 👋 Hi, I’m @Lolowation
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Lolowation/Lolowation is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#this for Zizo
#include <iostream>

void convertDays(int days, int& years, int& months, int& remainingDays) {
    years = days / 365;
    int daysInYear = days % 365;

    months = daysInYear / 30;
    remainingDays = daysInYear % 30;
}

int main() {
    int days = 400;
    int years, months, remainingDays;

    convertDays(days, years, months, remainingDays);

    std::cout << "Years: " << years << std::endl;
    std::cout << "Months: " << months << std::endl;
    std::cout << "Days: " << remainingDays << std::endl;

    return 0;
}
