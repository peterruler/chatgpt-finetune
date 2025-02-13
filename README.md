# Beschreibung
- ChatGPT Finetuning - Machen Sie ChatGPT zu einem sarkastischen Chat-Assistenten
- Basierend auf dem Projekt von [Jeff Heaton](https://github.com/jeffheaton/app_generative_ai)

## OpenAI API-Schlüssel abrufen
- Besuchen Sie die [OpenAI Plattform](https://platform.openai.com/settings/organization/billing/overview), um Ihren API-Schlüssel zu erhalten.

## Demo (Jupyter Notebook)
- Sie können das Jupyter Notebook auf [Google Colab](https://colab.research.google.com/) ausführen.

## Screenshot
![ChatGPT Finetuning](finetune.png?raw=true "ChatGPT Finetuning")

## Dateien im Projekt
- `sarcastic.jsonl`: Trainingsdaten für das Finetuning
- `sarcastic_val.jsonl`: Validierungsdaten für das Finetuning
- `t81_559_class_11_3_code.ipynb`: Jupyter Notebook mit dem Code für das Finetuning

## OpenAI API-Schlüssel in Google Colab hinterlegen
Um Ihren OpenAI API-Schlüssel sicher in Google Colab zu hinterlegen, folgen Sie diesen Schritten:

1. Öffnen Sie Ihr Jupyter Notebook auf [Google Colab](https://colab.research.google.com/).
2. Tragen Sie Ihren OpenAI API-Schlüssel manuell in den Google Colab Passwort-Save in der linken Spalte auf der Google Colab Oberfläche mit dem Schlüssel-Icon ein, um den API-Schlüssel sicher zu speichern.
Wählen Sie als Bezeichnung z.B. `OPENAI_API_KEY` und fügen sie den kopierten Openai-API-Schlüssel aus den [OpenAI Api Keys](https://platform.openai.com/settings/organization/api-keys) ein.
