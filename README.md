# Engagement-Predictor

Engagement-Predictor is a machine learning project that tries to answer an old question in military history: given what each side brings to the fight, who wins?

The model learns from historical engagements, starting with the public-domain CDB90 dataset of 660 battles and expanding toward modern conflicts, including the war in Ukraine. It looks past raw troop counts to the factors that decide battles: artillery and armor ratios, air superiority, naval fire support, surprise, terrain, defensive preparation, logistics, and technological edge. Instead of naming a winner, it gives a probability, along with a breakdown of which factors moved the odds and by how much.

An interactive Streamlit app lets you set up a scenario, replay a historical battle, or change a single variable, like doubling the defender’s artillery or taking away the attacker’s air cover, and watch the prediction respond.

To keep it honest, every prediction is benchmarked on held-out battles against classic combat models: the 3:1 rule, Lanchester’s laws, and Dupuy’s Quantified Judgment Model. Irregular and guerrilla warfare is flagged separately, since battlefield wins in those conflicts often don’t decide the war.

Inspired by grand strategy games like Hearts of Iron IV, but grounded in real data.

Status: early development.
