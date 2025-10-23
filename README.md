# ⚖️ MLS VAR Review Dashboard

---

## 🎯 Goal

To build an interactive tool that helps teams assess the likelihood of a Video Assistant Referee (VAR) review ruling in their favor, based on match context and historical data.

---

## 💡 Hypothesis

VAR decisions are not entirely random—factors such as match scoreline, home/away status, referee assignment, and match timing may influence whether a review favors a team.

---

## 🧠 Methods
	•	Scraped data from online sources to create a comprehensive database of all VAR reviews from the past three MLS seasons.
	•	Engineered filters that allow users to query by multiple match and referee conditions, such as:
	•	Scoreline
	•	Home vs. away status
	•	Match minute
	•	Referee name
	•	Type of review (penalty, offside, red card, etc.)
	•	Built an interactive dashboard that dynamically calculates the probability of a favorable decision given selected conditions.
	•	Designed with practical applications in mind — both for in-match challenge decisions and pre-match referee preparation.

---

## 📊 Example Use Case

A team considering a challenge for a no-call penalty could input:

Losing team, 80th minute, away from home, specific referee name.

The dashboard would return the percentage likelihood of a penalty being awarded in comparable historical situations — providing a quick, data-driven input to support decision-making.

---

## 🧩 Applications
	•	🏟️ In-Match Use: Inform challenge or review decisions.
	•	📋 Pre-Match Prep: Study referee tendencies and historical biases.
	•	📈 Strategic Analysis: Quantify potential impacts of officiating trends on team outcomes.

---

## 🖼️ Dashboard Preview

<img src="VAR%20Dash%20SS.png" width="50%">
