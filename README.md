<img src="https://i.imgur.com/Lz0p9i0.png"
     alt="Wokstar Logo"
     class="wokstar-logo" />

# Wokstar
By Panda Express Chefs

## Problem Statement
Users who possess basic cooking skills may want to try making Asian food because of their culture, background, or simply because it may sound appetizing, but a lack of ideas and guidance with or without ingredients may get in the user’s way. This leads them to spend a wasteful amount of time researching what recipes fit their tastes and needs.

## User Research

We conducted semi-structured interviews for all our users in our user research. We also classified users into 2 classes: **Novice Cook** and **Experienced Cook**

<table style="width: 100%;">
  <tr>
    <td valign="top" width="33%">
      <strong>Andrew</strong><br>
      <em>Novice Cook</em><br><br>
      "I don't have a lot of cooking equipment, so I prefer just eating at the dining hall."
    </td>
    <td valign="top" width="33%">
      <strong>Andy</strong><br>
      <em>Novice Cook</em><br><br>
      "I am a beginner at cooking. I don't try to cook the most difficult recipe."
    </td>
    <td valign="top" width="33%">
      <strong>Ethan</strong><br>
      <em>Experienced Cook</em><br><br>
      "I like cooking tomato-egg because it is easy to make and also I have all the necessary ingredients in the fridge."
    </td>
  </tr>
  <tr>
    <td valign="top" width="33%">
      <strong>Jennifer</strong><br>
      <em>Experienced Cook</em><br><br>
      "A lot of times I would be tired cooking, but I have to cook to prepare food for myself in the week anyways."
    </td>
    <td valign="top" width="33%">
      <strong>Jessie</strong><br>
      <em>Experienced Cook</em><br><br>
      "My grandmother passes down recipes of hers to us."
    </td>
    <td valign="top" width="33%">
      <strong>Olivia</strong><br>
      <em>Beginner Cook</em><br><br>
      "Time was the biggest barrier for me in cooking."
    </td>
  </tr>
  <tr>
    <td valign="top" width="33%">
      <strong>Molly</strong><br>
      <em>Beginner Cook</em><br><br>
      "I usually cook Chinese food because I am from China and convenience food like instant noodles and hotpot."
    </td>
    <td valign="top" width="33%">
      <strong>Rigo</strong><br>
      <em>Experienced Cook</em><br><br>
      "I lived with one person and we would cook for each other."
    </td>
    <td></td>
  </tr>
</table>

## Sketches and Storyboard


## Parallel Prototypes
We chose to integrate the **branching map system** (Prototype 1) because it is visually the most efficient for showing how changes to a user's kitchen inventory can unlock new recipes. Rather than presenting users with a traditional list of recipes, the branching map allows users to easily visualize the relationship between their available ingredients and potential dishes. Users can explore how adding or substituting certain ingredients expands their cooking possibilities, helping them make more informed decisions about what to purchase and prepare.

### Prototype 1: Branching exploration map
Users start at their current kitchen setup and follow branches such as “Add potato” to see newly available recipes.

![](https://i.imgur.com/BML9eDt.png)

### Prototype 2: Recipe comparison cards
Users see recipes grouped into “Ready now” and “One change away,” with each card explaining the required change.

![](https://i.imgur.com/6XlNtlk.png)

### Prototype 3: Guided decision flow
Users answer short questions such as “Can you add one ingredient?” and receive a focused recommendation, with an option to see alternatives.

![](https://i.imgur.com/FAxyXDb.png)


## Design Goals:
### Design Goal 1: Make Asian recipes easy to understand and follow.
**Goal**: Organize recipes into clear, manageable steps that help users cook efficiently without feeling overwhelmed.
\
Why it matters: In our user interviews, Jessie mentioned that he could cook almost any dish when provided with a concrete, step-by-step recipe. This suggests that clear recipe organization is important for helping users successfully prepare unfamiliar Asian dishes.

Our final system **fully reflects** this design goal. Our branching system provides concrete steps for each recipe and allows users to view beginner (more detailed) and concise steps. We also provide a full list of ingredients, necessary cooking equipment, cooking time, and other information for the user.

### Design Goal 2: Help users discover and prepare Asian dishes that match their interests and skill levels.
**Goal**: Allow users to find recipes based on their preferred cuisine, available ingredients, and cooking experience.
\
**Why it matters**: Our user research showed that people are interested in cooking Asian cuisine but may have different levels of experience and familiarity with certain dishes. For example, our interview participant Jennifer enjoyed cooking Asian food and felt confident following recipes when given clear, step-by-step instructions.

Our final system **mostly reflects** this design goal. We allow users to set a max difficulty on the recipes. Thus, the app caters to users of different cooking skill levels. We also allow users to choose what type of Asian cuisine they want to cook such as Chinese, Korean, Japanese etc. However, in order to further match users' interests, we could add more user preference settings, such as preferred flavors, dietary restrictions, favorite ingredients, and maximum cooking time. We could also incorporate a feedback system that learns from recipes users have liked, saved, or previously cooked. This will bolster our app's connection with users' individual tastes, lifestyles, and cooking goals.

## Demo Video
<iframe
    width="100%"
    height="450"
    src="https://www.youtube.com/embed/7Icxe1AHuwA"
    title="Wokstar Demo Video"
    frameborder="0"
    allowfullscreen>
</iframe>

*Note: this demo was recorded when the app was using a older frontend.*

## Usability Test Findings

## Usability Test Findings

| Finding | What We Would Change Next |
|---|---|
| Beginners were unsure where to start on the branching map. | Add a short walkthrough highlighting “Your kitchen” and the first branch. ✅ |
| Users wanted suggestions even when they lacked several ingredients. | Show the closest recipes and clearly list every missing item. ✅ |
| Recipe cards were easy to scan, but comparing missing ingredients across dishes took effort. | Highlight shared missing ingredients so users can see what one purchase would unlock. |
| Experienced cooks found the guided questions slower than browsing directly. | Add a “Skip questions and browse” option. |
| Entering ingredients manually felt tedious. | Add ingredient suggestions, common pantry presets, and a way to reuse a saved kitchen. |
| The branching map required too much scrolling on phones. | Offer a compact list view alongside the map. |

*Note: ✅ means suggested change was implemented.*

