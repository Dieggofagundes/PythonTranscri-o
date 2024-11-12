import whisper

modelo = whisper.load_model ("small")

resposta = modelo.transcribe("whatsApp Ptt 2024-10-30 at 17.07.42.ogg" ) 

print(resposta)

import speech_recognition as sr
from reportlab.lib.pagesizes import A4
from reportlab.pdfgen import canvas

def transcrever_audio_para_texto(C:\Users\dieggo\Desktop\Curso Python):
    recognizer = sr.Recognizer()
    with sr.AudioFile(C:\Users\dieggo\Desktop\Curso Python) as source:
        audio_data = recognizer.record(source)
        try:
            print("Transcrição concluída com sucesso.")
            return texto
        except sr.UnknownValueError:
            print("Não foi possível entender o áudio.")
            return ""
        except sr.RequestError:
            print("Erro na requisição ao serviço de reconhecimento.")
            return ""


def salvar_texto_em_pdf(texto, caminho_pdf):
    c = canvas.Canvas(caminho_pdf, pagesize=A4)
    width, height = A4

    linhas = texto.splitlines()
    text_obj = c.beginText(40, height - 40)
    text_obj.setFont("Helvetica", 12)

    for linha in linhas:
        text_obj.textLine(linha)
    c.drawText(text_obj)
    c.save()

# Caminhos dos arquivos
caminho_audio = "C:\Users\dieggo\Desktop\Curso Python"  
caminho_pdf = "transcricao.pdf"

# Etapas de transcrição e criação do PDF
texto_transcrito = transcrever_audio_para_texto(:\Users\dieggo\Desktop\Curso Python)
if texto_transcrito:
    salvar_texto_em_pdf(texto_transcrito, caminho_pdf)
    print("Arquivo PDF gerado com sucesso:", caminho_pdf)
else:
    print("Não foi possível gerar o PDF.")
