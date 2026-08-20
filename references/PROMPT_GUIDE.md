# Prompt Guide for a Non-Developer

The user should not need to learn “prompt engineering” before doing useful work. The skill should accept natural requests and improve them interactively.

Still, teach this simple five-part format when useful:

## O-C-C-E-R

1. **Objective** — What do you want to achieve?
2. **Context** — What exists today and who uses it?
3. **Constraints** — What cannot change? What technologies/environment are fixed?
4. **Evidence / examples** — Screenshots, files, sample inputs/outputs, logs, links.
5. **Result** — What observable result would make you say “this is correct”?

Example:

> Objective: I want to calculate the energy consumption of three machines and show it on a dashboard.
> Context: Measurements arrive every minute from Modbus meters on the factory network.
> Constraints: The collector must run on the existing Windows PC and cannot depend on cloud connectivity.
> Evidence: I have a CSV sample and the meter manual.
> Result: I can select a date and see consumption per machine and total, matching a manual calculation within the defined tolerance.

Do not require all five fields before helping. Use them as a diagnostic checklist and ask only for missing information that materially affects the next decision.
