# Notes

- projeto será um site ao qual vai integrar o chat gpt para quando você realizar o upload de algum video o chat gpt te da dicas e titulos e descrição automaticamente para esse video.

- Arquivo vite.config.ts - ao inves de chamar todos os caminhos pelo path usando ../../ - voce pode agora  utilizar @ para chamar
- Apenas na pasta source -- SRC = @

- Para rodar - npm run dev

notado que ele usa bastante flex e gap para estilização

FLEX-1 - OU W-FULL - VAI PREENCHER TODO ESPAÇO DO SITE

leading-relaxed - line-height


### SR-ONLY
  <label htmlFor="video">
    Carregar video
  </label>
  <input type="file" id='video' accept='video/mp4' className='sr-only'/>

.sr-only {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    white-space: nowrap;
    border-width: 0;
}

ELE VAI TIRAR OS COMPONENTES POREM VAI MANTER ELE NO DOM 

### Aspect ration 

vai definir um padrão de tamanho para que quando seja configurada não altere a resolução, está sendo utilizada nessa aplicação para colocar a imagem do video
 
.aspect-video {
    aspect-ratio: 16 / 9;
}

## Tec

- TS 
- TSX 
- tailwindCSS 
- lucide-react - npm i lucide-react - biblioteca de icones
- Radix ui
- shadcn/ui
  - Vai instalar automaticamente o tailwind e o radix unidos a ele
- Prisma 
- SQLite

