---
title: 'Documenten: machtigingen worden niet overgeërfd wanneer een document naar een nieuw project wordt verplaatst'
description: 'Wanneer een gebruiker een document naar een ander project verplaatst, erft het document het delen geen toestemmingen van het nieuwe project. Het document wordt niet gedeeld met de gebruikers aan wie het project wordt gedeeld. '
hidefromtoc: true
feature: Digital Content and Documents
exl-id: 56dfaf55-7438-4569-b9a1-b62fbdd3f4d9
source-git-commit: d4dd73ea9edc802c945ee7b8aa478bf18b1c662c
workflow-type: tm+mt
source-wordcount: '174'
ht-degree: 0%

---

# Documenten: machtigingen worden niet overgeërfd wanneer een document naar een nieuw project wordt verplaatst

<!-- This Known Issue is on the TOC for both Workfront and Workfront Proof-->

<!--Won't fix tab: Valid issue, won't fix.-->

Wanneer een gebruiker een document naar een ander project verplaatst, erft het document het delen geen toestemmingen van het nieuwe project. Het document wordt niet gedeeld met de gebruikers aan wie het project wordt gedeeld.

**Oplossing:**

1. Navigeer naar het bovenliggende object van het document, zoals Project, Task of Issue.

1. Verwijder overgeërfde machtigingen uit de lijst voor delen van het bovenliggende object door op de X naast de overgeërfde machtigingen te klikken en vervolgens op **[!UICONTROL Save]** te klikken.

1. Voeg overerfde machtigingen opnieuw toe door terug te navigeren naar de lijst voor gedeelde items van het bovenliggende object en op **[!UICONTROL Undo]** te klikken naast de overerfde machtigingen en vervolgens op **[!UICONTROL Save]** te klikken.

U kunt ook een notitie maken van de id van het document (in de URL van de [!UICONTROL Document Details] -pagina) en contact opnemen met de [!DNL Workfront] -klantenondersteuning.

_Eerste rapporteerde op 6 Januari, 2023._
