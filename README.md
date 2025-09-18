Clacky Chan is a custom made prototype split keyboard for testing out communication using trrs cables between the halves.

It consists of:

rp2040 pro micro
pcb's for each half and wire attached thumb keys as I want the thumbs to be tented just slightly on relation to the finger area.
It is completely diode free and takes 20 mins of soldering for each side. It is not the last time I will try a diode-free design :)
Its running my own firmware, zigmkay, which can be found here: https://github.com/StephanMoeller/zigmkay

![71d9d91a-8ce8-4dc4-b1a9-bd24813d666e](https://github.com/user-attachments/assets/3ee29972-4315-4a07-abc8-7d7b9e7b72ac)
![ad2c0e29-a139-48bc-9a63-2b7b12f0825a](https://github.com/user-attachments/assets/16eacefb-4dd3-4111-8600-1d8253eda8ac)
![b09ff933-2e11-4308-b0d9-10f68c65feef](https://github.com/user-attachments/assets/d984fd10-9ccc-4fe0-8f29-0581a453d0ea)
![bc37182f-509c-406f-89c6-056639b44986](https://github.com/user-attachments/assets/650d6fd1-2e8b-4b65-a3c5-8fd6e3627cab)
![bf89299e-6e8e-4636-850b-74c77fa247b9](https://github.com/user-attachments/assets/b58421bd-55e2-4c67-b82b-d63f9437d8fc)
![e1264128-50f4-48ad-9a02-e3029bf71215](https://github.com/user-attachments/assets/3a96ba25-775b-4b65-988f-5c62a6a1e3ef)
![ff60f66d-b6b9-4421-adec-dca49aa49fca](https://github.com/user-attachments/assets/700e411b-bc0a-42f3-a899-1d2d8428040f)
![8c7d04c5-575d-4bbf-8a1f-15eb03bb9990 (1)](https://github.com/user-attachments/assets/4ed62cde-bd84-4ece-80b8-4978292eda0b)
![dbb364ab-9d85-4f8b-a48c-94f8f26aa15f](https://github.com/user-attachments/assets/13c62a10-3876-4ad6-9944-8f54f75f3362)



PCB gerber files for production can be found in clackychan/production/clackychan.zig

Following picture uses wiring, eg. GPIO 6 is used as the single col and all the row pins can be determined as well. The thumb keys are wired to the GPIO 6 and then I choose GPIO 10 in the corner as the row.
<img width="1679" height="843" alt="image" src="https://github.com/user-attachments/assets/c3d4a3ce-5288-4084-a339-466c84dcdcbc" />

Ongoing OnShape repo with the tenting: https://cad.onshape.com/documents/76ee9714ee23fe3d9d1e73a4/w/b73638d5ae9d33482cab6d43/e/1ea8409974f0fb535c971db1
