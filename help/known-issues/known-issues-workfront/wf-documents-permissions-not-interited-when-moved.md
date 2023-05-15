---
title: "Documenten: Machtigingen worden niet overgeërfd wanneer een document naar een nieuw project wordt verplaatst."
description: 'Wanneer een gebruiker een document naar een ander project verplaatst, overerft het document geen machtigingen voor delen van het nieuwe project. Het document wordt niet gedeeld met de gebruikers aan wie het project wordt gedeeld. '
hidefromtoc: true
exl-id: 56dfaf55-7438-4569-b9a1-b62fbdd3f4d9
source-git-commit: 35fb85acf0c4b8675c3b6dad72c373ac6192055d
workflow-type: tm+mt
source-wordcount: '174'
ht-degree: 0%

---

# Documenten: Machtigingen worden niet overgeërfd wanneer een document naar een nieuw project wordt verplaatst

<!-- This Known Issue is on the TOC for both Workfront and Workfront Proof-->

<!--Won't fix tab: Valid issue, won't fix.-->

Wanneer een gebruiker een document naar een ander project verplaatst, erft het document het delen geen toestemmingen van het nieuwe project. Het document wordt niet gedeeld met de gebruikers aan wie het project wordt gedeeld.

**Oplossing:**

1. Navigeer naar het bovenliggende object van het document, zoals Project, Task of Issue.

1. Geërfte machtigingen verwijderen uit de lijst voor delen van het bovenliggende object door op de X naast de overgeërfde machtigingen te klikken en vervolgens op **[!UICONTROL Save]**.

1. Overerfde machtigingen opnieuw toevoegen door terug te navigeren naar de lijst voor gedeelde items van het bovenliggende object en op **[!UICONTROL Undo]** naast overgeërfde machtigingen klikt u op **[!UICONTROL Save]**.

U kunt ook een notitie maken van de id van het document (in de URL van het dialoogvenster [!UICONTROL Document Details] pagina) en contact opnemen [!DNL Workfront] klantenondersteuning.

_Eerste rapportage op 6 januari 2023._
