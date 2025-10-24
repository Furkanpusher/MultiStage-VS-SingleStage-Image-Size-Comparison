### Image'lerin build edilmesi

Kodların olduğu klasöre gidiş yaptıktan sonra aşağıdaki kodlar ile İmage'ler build edilebilir.

```bash
docker build -t multi-stage-docker -f Dockerfile.MultiStage .
docker build -t single-stage-docker -f Dockerfile.SingleStage .

### Image'ları build ettikten sonra terminalden aşağıdaki komut ile bu image'ların boyutlarını karşılaştırabilirsiniz.

```bash
docker images | grep stage-docker


