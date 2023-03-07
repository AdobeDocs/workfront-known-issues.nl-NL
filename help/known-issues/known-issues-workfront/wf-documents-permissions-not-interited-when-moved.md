---
title: "Documenten: Machtigingen worden niet overgeërfd wanneer een document naar een nieuw project wordt verplaatst."
description: "Wanneer een gebruiker een document naar een ander project verplaatst, erft het document het delen geen toestemmingen van het nieuwe project. Het document wordt niet gedeeld met de gebruikers aan wie het project wordt gedeeld. "
hidefromtoc: true
source-git-commit: 05592905aecebd7c6f99f4ffa7513630baae5692
workflow-type: tm+mt
source-wordcount: '177'
ht-degree: 0%

---


# Documenten: Machtigingen worden niet overgeërfd wanneer een document naar een nieuw project wordt verplaatst

<!-- This Known Issue is on the TOC for both Workfront and Workfront Proof-->

Wanneer een gebruiker een document naar een ander project verplaatst, erft het document het delen geen toestemmingen van het nieuwe project. Het document wordt niet gedeeld met de gebruikers aan wie het project wordt gedeeld.

**Oplossing:**

1. Navigeer naar het bovenliggende object van het document, zoals Project, Task of Issue.

1. Geërfte machtigingen verwijderen uit de lijst voor delen van het bovenliggende object door op de X naast de overgeërfde machtigingen te klikken en vervolgens op **[!UICONTROL Save]**.

1. Overerfde machtigingen opnieuw toevoegen door terug te navigeren naar de lijst voor gedeelde items van het bovenliggende object en op **[!UICONTROL Undo]** naast overgeërfde machtigingen klikt u op **[!UICONTROL Save]**.

U kunt ook een notitie maken van de id van het document (in de URL van de pagina Documentdetails) en contact opnemen met de klantenondersteuning van Workfront.

_Eerste rapportage op 6 januari 2023._

