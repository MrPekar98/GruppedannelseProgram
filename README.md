# Gruppedannelse program
# Skrive regler
- 4 spaces.
- Oneliner uden curly braces.
- Curlybraces rykkes ned.
- Husk masser af kommentarer på engelsk.
- Kommentarer skal være tilføjet inden commit.
- Husk passende afsnit.
- Variabler starter med småt bogstav.
- Ord skilles med stort bogstav og ikke underscore.
- Symbolske konstanter (definitions og const) skrives med capital letters for alle bogstaver.
- Symbolske variabler adskilles med underscore.

# Program vejledning


# Program struktur
Input parametre:
- Antal studerende.
- Gruppestørrelse.

# Struct:
Members:
- char *navn.
- char køn.

struct BelbinTestResult:
- int plant.
- int MonitorEvaluator.
- int specialist.
- int shaper.
- int implementer.
- int CompleterFinisher.
- int coordinator.
- int teamworker.
- int ResourceInvestigator.

# Main
enum PersonalityTypes {Type1 = 1, Type2, Type3, Type4};

int amountOfStudents, groupSize;

personData persons[amountOfStudents];

group groups[amountOfStudents / GROUP_MAX_SIZE + 1]; (GROUP_MAX_SIZE = 6)
