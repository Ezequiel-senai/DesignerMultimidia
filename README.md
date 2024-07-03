# Técnico em Recursos Educacionais - Designer Multimídia
## Descrição da Atividade  

> [!NOTE]
> Orientações gerais <code>GITHUB</code>.
> Para avaliar seus conhecimentos técnicos, escolha um dos temas abaixo para customizar. Alguns itens foram sugeridos no documento base, mas você é livre para propor soluções e itens, caso ache necessário.

> [!TIP]
> 1 – Origamis:
> [Storyboard](https://pages.github.com/).
> Paleta de cores para este projeto
`#f37140`, `#faa754`, `#fcf27d`, `#06689d`, `#014466`

> [!TIP]
> 2 – Como fazer batata frita:
> [Storyboard](https://pages.github.com/).
> Paleta de cores para este projeto
`#f3f9f5`, `#d1eada`, `#90d4d3`, `#31a2dc`, `#3665b0`

> [!IMPORTANT]
> O objetivo é conhecer suas experiências práticas, portanto, fique tranquilo, todas as entregas serão avaliadas!

> [!CAUTION]
> Caso não consiga acessar algum arquivo ou documentação, tire suas dúvidas o mais breve possível pelo mesmo email em que o teste deve ser entregue.

> [!WARNING]
>Boa sorte!


## Recursos para usar no teste:
## Accordion 1

```html
<div class="accordion" id="accordionExample">
    <div class="accordion-item">
        <h4 class="accordion-header" id="headingOne">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                data-bs-target="#collapseOne" aria-expanded="false" aria-controls="collapseOne">
                Lorem Ipsum
            </button>
        </h4>
        <div id="collapseOne" class="accordion-collapse collapse" aria-labelledby="headingOne"
            data-bs-parent="#accordionExample">
            <div class="accordion-body">
                <p>
                    Lorem Ipsum
                </p>
            </div>
        </div>
    </div>
    <div class="accordion-item">
        <h4 class="accordion-header" id="headingTwo">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                Lorem Ipsum 2
            </button>
        </h4>
        <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo"
            data-bs-parent="#accordionExample">
            <div class="accordion-body">
                <p>
                    Lorem Ipsum 2
                </p>
            </div>
        </div>
    </div>
    <div class="accordion-item">
        <h4 class="accordion-header" id="headingThree">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                data-bs-target="#collapseThree" aria-expanded="false"
                aria-controls="collapseThree">
                Lorem Ipsum 3
            </button>
        </h4>
        <div id="collapseThree" class="accordion-collapse collapse"
            aria-labelledby="headingThree" data-bs-parent="#accordionExample">
            <div class="accordion-body">
                <p>
                    Lorem Ipsum 3
                </p>
            </div>
        </div>
    </div>
</div>
```

## Accordion 2

```html
<div class="accordion accordion-flush py-2" id="accordionFlushExample">
    <div class="accordion-item">
        <h2 class="accordion-header" id="flush-headingOne">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                data-bs-target="#flush-collapseOne" aria-expanded="false"
                aria-controls="flush-collapseOne">
                Lorem Ipsum 1
            </button>
        </h2>
        <div id="flush-collapseOne" class="accordion-collapse collapse"
            aria-labelledby="flush-headingOne" data-bs-parent="#accordionFlushExample">
            <div class="accordion-body">
                <p>
                    Lorem Ipsum 1
                </p>
            </div>
        </div>
    </div>
    <div class="accordion-item">
        <h2 class="accordion-header" id="flush-headingTwo">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                data-bs-target="#flush-collapseTwo" aria-expanded="false"
                aria-controls="flush-collapseTwo">
                Lorem Ipsum 2
            </button>
        </h2>
        <div id="flush-collapseTwo" class="accordion-collapse collapse"
            aria-labelledby="flush-headingTwo" data-bs-parent="#accordionFlushExample">
            <div class="accordion-body">
                <p>
                    Lorem Ipsum 2
                </p>
            </div>
        </div>
    </div>
    <div class="accordion-item">
        <h2 class="accordion-header" id="flush-headingThree">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                data-bs-target="#flush-collapseThree" aria-expanded="false"
                aria-controls="flush-collapseThree">
                Lorem Ipsum 3
            </button>
        </h2>
        <div id="flush-collapseThree" class="accordion-collapse collapse"
            aria-labelledby="flush-headingThree" data-bs-parent="#accordionFlushExample">
            <div class="accordion-body">
                <p>
                    Lorem Ipsum 3
                </p>
            </div>
        </div>
    </div>
</div>
```

## Accordion 3

```html
<ul uk-accordion class="">
    <li>
        <a class="uk-accordion-title" href="#">Lorem Ipsum 1</a>
        <div class="uk-accordion-content">
            <p>
                Lorem Ipsum 1
            </p>
        </div>
    </li>
    <li>
        <a class="uk-accordion-title" href="#">Lorem Ipsum 2</a>
        <div class="uk-accordion-content">
            <p>
                Lorem Ipsum 2
            </p>
        </div>
    </li>
    <li>
        <a class="uk-accordion-title" href="#">Lorem Ipsum 3</a>
        <div class="uk-accordion-content">
            <p>
                Lorem Ipsum 3
            </p>
        </div>
    </li>
</ul>
```

## Audio
```html
<div class="row py-2">
    <i class="bi bi-mic-fill cor1 d-flex justify-content-center" style="font-size:3rem; "></i>
</div>
<div class="mx-auto">
    <audio class="uk-align-center" controls controlslist="nodownload">
        <source src="#"
            type="audio/mp3">
    </audio>
</div>
<div class="mx-auto">
    <button class="uk-button-default rounded uk-align-center ativo" type="button"
        uk-toggle="target: #audio-1; animation:  uk-animation-slide-left, uk-animation-slide-bottom"
        aria-expanded="false">
        <h3 class="m-3">Transcrição</h3>
    </button>
    <div id="audio-1" class="uk-card uk-card-default uk-card-body uk-margin-small rounded py-5"
        hidden="">
        <p>
            #
        </p>
    </div>
</div>
```

## Box Comum
```html
<!-- Box -->
<div class="row">
    <div class="col-lg-6 py-5">
        <div class="box">
            <h3>Box</h3>
            <p>
                Lorem ipsum
            </p>
        </div>
    </div>
    <div class="col-lg-6 py-5">
        <div class="box2">
            <h3>Box Title</h3>
            <p>
            Lorem Ipsum
            </p>
        </div>
    </div>
</div>
```
## Box Importante
```html
<!-- Importante! -->
<div class="col-lg-8 mx-auto py-5">
    <div class="box importante">
        <div class="d-flex justify-content-center d-sm-none mx-auto">
            <i class="bx bi bi-exclamation-circle vermelho-importante bx-tada"></i>
        </div>
        <div class="d-flex  align-items-center container">
        <div class="col-lg-10 p-2">
            <div class="row">
                <h3>Importante!</h3>
                <p>
                Lorem Ipsum
                </p>
            </div>
        </div>
        <div class="col-lg-2 ">
            <div class="d-flex d-none d-sm-block d-md-block d-lg-block">
                <i class="bx bi bi-exclamation-circle vermelho-importante bx-tada"></i>
            </div>
        </div>
    </div>
</div>
```
## Box Saiba mais...
```html
<!-- Saiba mais... -->
<div class="col-lg-8 mx-auto py-5">
    <div class="box saibamais">
        <div class="d-flex justify-content-center d-sm-none mx-auto">
            <i class="bx bi bi bi-search verde-saibamais bx-tada"></i>
        </div>
        <div class="d-flex  align-items-center container">
            <div class="col-lg-10 p-2">
                <div class="row">
                <h3>Saiba mais...</h3>
                <p>
                Lorem Ipsum
                </p>
                </div>
            </div>
            <div class="col-lg-2 ">
                <div class="d-flex d-none d-sm-block d-md-block d-lg-block">
                    <i class="bx bi bi bi-search verde-saibamais bx-tada"></i>
                </div>
            </div>
        </div>
    </div>
</div>
```
## Box Dica
```html
<!-- Dica -->
<div class="col-lg-8 mx-auto py-5">
    <div class="box dica">
        <div class="d-flex justify-content-center d-sm-none mx-auto">
            <i class='bx bx-bulb laranja-dica bx-tada'></i>
        </div>
        <div class="d-flex  align-items-center container">
            <div class="col-lg-10 p-2">
                <div class="row">
                <h3>Dica</h3>
                <p>
                Lorem Ipsum
                </p>
                </div>
            </div>
            <div class="col-lg-2 ">
                <div class="d-flex d-none d-sm-block d-md-block d-lg-block">
                    <i class='bx bx-bulb laranja-dica bx-tada'></i>
                </div>
            </div>
        </div>
    </div>
</div>
```
## Box Você sabia?
```html
<!-- Você sabia? -->
<div class="col-lg-8 mx-auto py-5">
    <div class="box vcsabia">
        <div class="d-flex justify-content-center d-sm-none mx-auto">
            <i class="bx bi bi-question-circle roxo-vcsabia bx-tada"></i>
        </div>
        <div class="d-flex  align-items-center container">
            <div class="col-lg-10 p-2">
                <div class="row">
                <h3>Você sabia?</h3>
                <p>
                Lorem Ipsum
                </p>
                </div>
            </div>
        <div class="col-lg-2 ">
            <div class="d-flex d-none d-sm-block d-md-block d-lg-block">
                <i class="bx bi bi-question-circle roxo-vcsabia bx-tada"></i>
            </div>
        </div>
    </div>
</div>
```
## Box PDF
```html
<!-- Pdf? -->
<div class="col-lg-8 mx-auto py-5">
    <div class="box pdf">
        <div class="d-flex justify-content-center d-sm-none mx-auto">
            <i class="bx bi bi-file-earmark-pdf cinza-pdf bx-tada"></i>
        </div>
        <div class="d-flex  align-items-center container">
            <div class="col-lg-10 p-2">
                <div class="row">
                <h3>PDF</h3>
                <p>
                Lorem Ipsum
                </p>
                </div>
            </div>
            <div class="col-lg-2 ">
                <div class="d-flex d-none d-sm-block d-md-block d-lg-block">
                    <i class="bx bi bi-file-earmark-pdf cinza-pdf bx-tada"></i>
                </div>
            </div>
        </div>
    </div>
</div>
```

## Card Top
```html
<div class="uk-card uk-card-default">
    <div class="uk-card-media-top">
        <a data-fancybox="zoom" data-src="#imagem" data-caption="">
            <img src="#imagem" class="img-fluid" alt="">
        </a>
    </div>
    <div class="uk-card-body">
        <h3 class="uk-card-title">Lorem Ipsum</h3>
        <p>
            Lorem Ipsum
        </p>
    </div>
</div>
```

## Card Bottom
```html
<div class="uk-card uk-card-default">
    <div class="uk-card-body">
        <h3 class="uk-card-title">Lorem Ipsum</h3>
        <p>
            Lorem Ipsum
        </p>
    </div>
    <div class="uk-card-media-bottom">
        <a data-fancybox="zoom" data-src="#imagem" data-caption="">
            <img src="#imagem" class="img-fluid" alt="">
        </a>
    </div>
</div>
```

## Collapse show
```html
<div class="d-grid gap-2">
    <button href="#toggle-animation" class="uk-button uk-button-default py-1" type="button"
        uk-toggle="target: #toggle-animation; animation: uk-animation-fade "
        aria-expanded="false">
        Lorem Ipsum
    </button>
</div>
<div id="toggle-animation" class="uk-card uk-card-default uk-card-body uk-margin-small" hidden="">
    <p>
        Lorem Ipsum
    </p>
</div>
```

## Collapse Left
```html
<div class="d-grid gap-2">
    <button class="uk-button uk-button-default py-1" type="button"
        uk-toggle="target: #toggle-animation-multiple; animation:  uk-animation-slide-left, uk-animation-slide-bottom"
        aria-expanded="false">
        Lorem Ipsum
    </button>
</div>
<div id="toggle-animation-multiple" class="uk-card uk-card-default uk-card-body uk-margin-small"
hidden="">
    <p>
    Lorem Ipsum
    </p>
</div>

```

## Exercício combobox
```html
<div class="row py-3">
    <div class="col-lg-10 mx-auto py-5 border rounded" id="1-combobox1">
        <div class=" m-3">
            <p><strong>1.</strong> Lorem Ipsum</p>

            <div class="row">
                <div class="col-md-10 col-sm-10 col-lg-10 px-3">
                    <p>A) Lorem Ipsum</p>
                </div>
                <div class="col-md-12 col-sm-12 col-lg-2 px-2">
                    <div id="testBefore1" class="dropdown">
                        <div class="btn-group d-grid mx-auto px-3">
                            <select name="1" id="1-combobox-1" class="form-select select1"
                                aria-label="example">
                                <option disabled="" selected="">Selecione
                                </option>
                                <option value="1">Análise</option>
                                <option value="2">Avaliação </option>
                                <option value="3">Desenvolvimento </option>
                                <option value="4">Design </option>
                                <option value="5">Implementação </option>
                            </select>
                        </div>
                    </div>
                </div>
            </div>
            <hr>
            <div class="row">
                <div class="col-md-10 col-sm-10 col-lg-10 px-3">
                    <p>B) Lorem Ipsum</p>
                </div>
                <div class="col-md-12 col-sm-12 col-lg-2 px-2">
                    <div id="testBefore2" class="dropdown">
                        <div class="btn-group d-grid mx-auto px-3">
                            <select name="2" id="1-combobox-2" class="form-select select2"
                                aria-label="example">
                                <option disabled="" selected="">Selecione
                                </option>
                                <option value="1">Análise </option>
                                <option value="2">Avaliação </option>
                                <option value="3">Desenvolvimento </option>
                                <option value="4">Design </option>
                                <option value="5">Implementação </option>
                            </select>
                        </div>
                    </div>
                </div>
            </div>
            <hr>
            <div class="row ">
                <div class="col-md-10 col-sm-10 col-lg-10 px-3">
                    <p>C) Lorem Ipsum</p>
                </div>
                <div class="col-md-12 col-sm-12 col-lg-2 px-2">
                    <div id="testBefore3" class="dropdown">
                        <div class="btn-group d-grid mx-auto px-3">
                            <select name="3" id="1-combobox-3" class="form-select select3"
                                aria-label="example">
                                <option disabled="" selected="">Selecione
                                </option>
                                <option value="1">Análise </option>
                                <option value="2">Avaliação </option>
                                <option value="3">Desenvolvimento </option>
                                <option value="4">Design </option>
                                <option value="5">Implementação </option>
                            </select>
                        </div>
                    </div>
                </div>
            </div>
            <hr>
            <div class="row ">
                <div class="col-md-10 col-sm-10 col-lg-10 px-3">
                    <p>D) Lorem Ipsum</p>
                </div>
                <div class="col-md-12 col-sm-12 col-lg-2 px-2">
                    <div id="testBefore4" class="dropdown">
                        <div class="btn-group d-grid mx-auto px-3">
                            <select name="4" id="1-combobox-4" class="form-select select4"
                                aria-label="example">
                                <option disabled="" selected="">Selecione
                                </option>
                                <option value="1">Análise </option>
                                <option value="2">Avaliação </option>
                                <option value="3">Desenvolvimento </option>
                                <option value="4">Design </option>
                                <option value="5">Implementação </option>
                            </select>
                        </div>
                    </div>
                </div>
            </div>
            <hr>
            <div class="row ">
                <div class="col-md-10 col-sm-10 col-lg-10 px-3">
                    <p class="my-n1">E) Lorem Ipsum</p>
                </div>
                <div class="col-md-12 col-sm-12 col-lg-2 px-2">
                    <div id="testBefore5" class="dropdown">
                        <div class="btn-group d-grid mx-auto px-3">
                            <select name="5" id="1-combobox-5" class="form-select select5"
                                aria-label="example">
                                <option disabled="" selected="">Selecione
                                </option>
                                <option value="1">Análise </option>
                                <option value="2">Avaliação </option>
                                <option value="3">Desenvolvimento </option>
                                <option value="4">Design </option>
                                <option value="5">Implementação </option>
                            </select>
                        </div>
                    </div>
                </div>
            </div>
            <div class="gy-4 m-2" id="1-vr-button-combobox1">
                <div class="row">
                    <div class="d-grid gap-2 col-md-3 mx-auto">
                        <button data-name="#1-resposta-combobox1" id="1-resposta-combobox1"
                            class="btn border uk-button-primary">
                            <span>Verificar Resposta</span>
                        </button>
                    </div>
                </div>
            </div>
            <div class="collapse mt-2" id="1-collapse-combobox1-0">
                <div class="card  shadow">
                    <div class="card-header">
                        <div class="card-title d-inline-flex align-baseline">
                            <i class="bi bi-exclamation-circle"></i> <span class="ms-1">
                                Atenção!</span>
                        </div>
                    </div>
                    <div class="card-body p-3">
                        Selecione todas as alternativas
                        do exercício.<p></p>
                    </div>
                </div>
            </div>
            <div class="collapse" id="1-collapse-combobox1-1">
                <div id="resp" class="card  shadow">
                    <div class="card-header">
                        <div class="card-title d-inline-flex align-baseline">
                            <i class="bi bi-check-circle"></i><span class="ms-1">Parabéns!
                                Resposta
                                correta.</span>
                        </div>
                    </div>
                    <div class="card-body   p-3">
                        <p>Você associou corretamente etapas de desenvolvimento de curso EAD. </p>
                    </div>
                </div>
            </div>
            <div class="collapse" id="1-collapse-combobox1-2">
                <div class="card  shadow">
                    <div class="card-header">
                        <div class="card-title d-inline-flex align-baseline">
                            <i class="bi bi-exclamation-circle"></i> <span class="ms-1">Ops!
                                Tente
                                novamente.</span>
                        </div>
                    </div>
                    <div class="card-body p-3">
                        <p>Retorne ao conteúdo e estude com atenção as etapas de desenvolvimento de
                            curso
                            EAD. </p>
                    </div>
                </div>
            </div>
            <div class="collapse" id="1-collapse-combobox1-3">
                <div class="card  shadow">
                    <div class="card-header">
                        <div class="card-title d-inline-flex align-baseline">
                            <i class="bi bi-x-circle"></i> <span class="ms-1">Resposta
                                incorreta.</span>
                        </div>
                    </div>
                    <div class="card-body p-3">
                        <p>
                            Resposta incorreta. As respostas corretas são:
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
```

## Exercício escolha única
```html
<div class="row py-3">
    <div class="col-lg-10 mx-auto py-5 border rounded">
        <div class="m-3">
            <p><strong>2.</strong> Lorem Ipsum
            </p>
        </div>
        <div class="row m-2">
            <div class="list-group-checkable d-grid gap-2" id="alternativas-escolha-unica-1">
                <input class="list-group-item-check pe-none" type="radio" name="list-unica-escolha-1"
                    id="exercicio-escolha-unica-1" data-exercicio1="1" data-alternativa1="a">
                <label class="list-group-item  border rounded-3 py-3" for="exercicio-escolha-unica-1">
                    <div class="row">
                        <p class="my-n1"> A) Lorem Ipsum
                        </p>
                    </div>
                </label>
                <input class="list-group-item-check pe-none" type="radio" name="list-unica-escolha-1"
                    id="exercicio-escolha-unica-2" data-exercicio1="1" data-alternativa1="b">
                <label class="list-group-item border rounded-3 py-3" for="exercicio-escolha-unica-2">
                    <div class="row">
                        <p class="my-n1">B) Lorem Ipsum
                        </p>
                    </div>
                </label>
                <input class="list-group-item-check pe-none " type="radio" name="list-unica-escolha-1"
                    id="exercicio-escolha-unica-3" data-exercicio1="1" data-alternativa1="c">
                <label class="list-group-item border rounded-3 py-3" for="exercicio-escolha-unica-3">
                    <div class="row">
                        <p class="my-n1">C) Lorem Ipsum
                        </p>
                    </div>
                </label>
                <input class="list-group-item-check pe-none " type="radio" name="list-unica-escolha-1"
                    id="exercicio-escolha-unica-4" data-exercicio1="1" data-alternativa1="d">
                <label class="list-group-item border rounded-3 py-3" for="exercicio-escolha-unica-4">
                    <div class="row">
                        <p class="my-n1"> D) Lorem Ipsum
                        </p>
                    </div>
                </label>
                <input class="list-group-item-check pe-none " type="radio" name="list-unica-escolha-1"
                    id="exercicio-escolha-unica-5" data-exercicio1="1" data-alternativa1="e">
                <label class="list-group-item border rounded-3 py-3" for="exercicio-escolha-unica-5">
                    <div class="row">
                        <p class="my-n1"> E) Lorem Ipsum
                        </p>
                    </div>
                </label>
            </div>
        </div>
        <div class="row m-2">
            <div class="collapse" id="collapse-ex1-1">
                <!-- mudar o ID de acordo com a questão para não dar conflito pois é identificação para chamar o feedback -->
                <div class="card border shadow">
                    <div class="card-header">
                        <div class="card-title d-inline-flex align-baseline"><i
                                class="bi bi-check-circle"></i><span class="ms-1">Parabéns!
                                Resposta
                                correta.</span>
                        </div>
                    </div>
                    <div class="card-body p-3">
                        <p>
                            Lorem Ipsum
                        </p>
                    </div>
                </div>
            </div>
            <!-- collapsed de resposta incorreta 1 -->
            <div class="collapse" id="collapse-ex1-2">
                <div class="card border  shadow">
                    <div class="card-header">
                        <div class="card-title d-inline-flex align-baseline"><i
                                class="bi bi-exclamation-circle"></i>
                            <span class="ms-1">Ops!
                                Tente
                                novamente.</span>
                        </div>
                    </div>
                    <div class="card-body p-3 text-black-75">
                        <p>
                            Lorem Ipsum
                        </p>
                    </div>
                </div>
            </div>
            <!-- collapsed de resposta incorreta 2 -->
            <div class="collapse" id="collapse-ex1-3">
                <div class="card border shadow">
                    <div class="card-header">
                        <div class="card-title d-inline-flex align-baseline"><i
                                class="bi bi-x-circle"></i>
                            <span class="ms-1">Resposta
                                incorreta.</span>
                        </div>
                    </div>
                    <div class="card-body p-3">
                        <p>
                            Lorem Ipsum
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
```

## Exercício múltipla escolha
```html
<div class="row py-3">
    <div class="col-lg-10 mx-auto py-5 border rounded" id="ex1_multi-tf">
        <div class="p-3 gy-4">
            <p><strong>5.</strong> Lorem Ipsum
            </p>
        </div>
        <div class="gy-4">
            <div class="row px-3 rounded">
                <p>A) Lorem Ipsum
                </p>
                <div class="row">
                    <div class="col-lg-3 mx-auto">
                        <div class="list-group list-group-radio d-grid gap-2 border-0">
                            <div class="position-relative">
                                <input class="form-check-input position-absolute top-50 end-0 me-3 fs-5"
                                    type="radio" name="1-ex-multi-tf-A" id="1-ex-multi-tf-1" value="">
                                <label class="list-group-item py-3 pe-5" for="1-ex-multi-tf-1">
                                    <strong class="fw-semibold">Verdadeira</strong>
                                </label>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-3 mx-auto">
                        <div class="list-group list-group-radio d-grid gap-2 border-0">
                            <div class="position-relative">
                                <input class="form-check-input position-absolute top-50 end-0 me-3 fs-5"
                                    type="radio" name="1-ex-multi-tf-A" id="1-ex-multi-tf-2" value="">
                                <label class="list-group-item py-3 pe-5" for="1-ex-multi-tf-2">
                                    <strong class="fw-semibold">Falsa</strong>
                                </label>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <hr class="center">
            <br>
            <div class="row px-3 rounded">
                <p>
                    B) Lorem Ipsum
                </p>
                <div class="row">
                    <div class="col-lg-3 mx-auto">
                        <div class="list-group list-group-radio d-grid gap-2 border-0">
                            <div class="position-relative">
                                <input class="form-check-input position-absolute top-50 end-0 me-3 fs-5"
                                    type="radio" name="1-ex-multi-tf-B" id="1-ex-multi-tf-3" value="">
                                <label class="list-group-item py-3 pe-5" for="1-ex-multi-tf-3">
                                    <strong class="fw-semibold">Verdadeira</strong>
                                </label>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-3 mx-auto">
                        <div class="list-group list-group-radio d-grid gap-2 border-0">
                            <div class="position-relative">
                                <input class="form-check-input position-absolute top-50 end-0 me-3 fs-5"
                                    type="radio" name="1-ex-multi-tf-B" id="1-ex-multi-tf-4" value="">
                                <label class="list-group-item py-3 pe-5" for="1-ex-multi-tf-4">
                                    <strong class="fw-semibold">Falsa</strong>
                                </label>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <hr class="center">
            <div class="row px-3 rounded">
                <p>
                    C) Lorem Ipsum
                </p>
                <div class="row mx-auto">
                    <div class="col-lg-3 mx-auto">
                        <div class="list-group list-group-radio d-grid gap-2 border-0">
                            <div class="position-relative">
                                <input class="form-check-input position-absolute top-50 end-0 me-3 fs-5"
                                    type="radio" name="1-ex-multi-tf-C" id="1-ex-multi-tf-5" value="">
                                <label class="list-group-item py-3 pe-5" for="1-ex-multi-tf-5">
                                    <strong class="fw-semibold">Verdadeira</strong>
                                </label>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-3 mx-auto">
                        <div class="list-group list-group-radio d-grid gap-2 border-0">
                            <div class="position-relative">
                                <input class="form-check-input position-absolute top-50 end-0 me-3 fs-5"
                                    type="radio" name="1-ex-multi-tf-C" id="1-ex-multi-tf-6" value="">
                                <label class="list-group-item py-3 pe-5" for="1-ex-multi-tf-6">
                                    <strong class="fw-semibold">Falsa</strong>
                                </label>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <br>
        <div class="collapse mt-20" id="collapse-multi-tf-ex1-seleciona">
            <div class="card mt-20 shadow">
                <div class="card-header">
                    <div class="card-title d-inline-flex align-baseline">
                        <i class="bi bi-exclamation-circle"></i>
                        <span class="ms-1">
                            Atenção!
                        </span>
                    </div>
                </div>
                <div class="card-body   p-3">
                    <p>Selecione todas as alternativas do exercício.</p>
                </div>
            </div>
        </div>
        <div class="collapse mt-20" id="collapse-multi-tf-ex1-certo">
            <div class="card mt-20 shadow">
                <div class="card-header">
                    <div class="card-title d-inline-flex align-baseline">
                        <i class="bi bi-check-circle"></i><span class="ms-1">Parabéns!
                            Resposta
                            correta.</span>
                    </div>
                </div>
                <div class="card-body p-3">
                    <p>Lorem Ipsum</p>
                </div>
            </div>
        </div>
        <div class="collapse mt-20" id="collapse-multi-tf-ex1-tentativa1">
            <div class="card mt-20 shadow">
                <div class="card-header">
                    <div class="card-title d-inline-flex align-baseline">
                        <i class="bi bi-x-circle"></i> <span class="ms-1">Resposta
                            incorreta.</span>
                    </div>
                </div>
                <div class="card-body p-3">
                    <p>Tente outra vez! Lorem Ipsum.
                    </p>
                </div>
            </div>
        </div>
        <div class="collapse mt-20" id="collapse-multi-tf-ex1-errada">
            <div class="card mt-20 shadow">
                <div class="card-header">
                    <div class="card-title d-inline-flex align-baseline">
                        <i class="bi bi-x-circle"></i> <span class="ms-1">Resposta
                            incorreta.</span>
                    </div>
                </div>
                <div class="card-body p-3">
                    <p>
                         Lorem Ipsum
                    </p>
                </div>
            </div>
        </div>
        <div class="gy-4 m-2" id="vr-button1multi-tf">
            <div class="row">
                <div class="d-grid gap-2 col-md-3 mx-auto p-3">
                    <button class="btn border" onClick="RespostaTrueOrFalse1();"><span>Verificar
                            Resposta</span></button>
                </div>
            </div>
        </div>
    </div>
</div>
```

## Exercício verdadeiro ou falso
```html
<div class="row py-3">
    <div class="col-lg-10 mx-auto py-5 border rounded">
        <div class="p-3 gy-4">
            <p><strong>4.</strong> Lorem Ipsum
            </p>
        </div>
        <div class="gy-4">
            <div class="row" id="verdadeiro">
                <div class="d-grid gap-2 col-md-3 mx-auto p-3 ">
                    <button id="verdadeiro" class="uk-button uk-button-default py-2"
                        data-bs-toggle="collapse" data-bs-target="#collapse-tf-ex1-1"
                        aria-expanded="verdadeiro" aria-controls="collapse-tf-ex1-1"
                        onclick="verdadeiro();"><span>Verdadeira</span></button>
                </div>
                <div class="d-grid gap-2 col-md-3 mx-auto p-3">
                    <button id="falso" class="uk-button uk-button-default py-2"
                        data-bs-toggle="collapse" data-bs-target="#collapse-tf-ex1-2"
                        aria-expanded="false" aria-controls="collapse-tf-ex1-2"
                        onclick="falso();"><span>Falsa</span></button>
                </div>
            </div>
        </div>
        <div class="collapse mt-20" id="collapse-tf-ex1-1">
            <div class="card mt-20 shadow">
                <div class="card-header">
                    <div class="card-title d-inline-flex align-baseline">
                        <i class="bi bi-check-circle"></i><span class="ms-1">Parabéns!
                            Resposta
                            correta.</span>
                    </div>
                </div>
                <div class="card-body   p-3">
                    <p>
                        Lorem Ipsum
                    </p>
                </div>
            </div>
        </div>
        <div class="collapse mt-20" id="collapse-tf-ex1-2">
            <div class="card mt-20 shadow">
                <div class="card-header">
                    <div class="card-title d-inline-flex align-baseline">
                        <i class="bi bi-x-circle"></i> <span class="ms-1">Resposta
                            incorreta.</span>
                    </div>
                </div>
                <div class="card-body p-3">
                    <p>
                        Lorem Ipsum
                    </p>
                </div>
            </div>
        </div>
    </div>
</div>
```

## Exercício múltipla escolha verdadeiro ou falso
```html
<div class="row py-3">
    <div class="col-lg-10 mx-auto py-5 border rounded" id="ex1_multi-tf">
        <div class="p-3 gy-4">
            <p><strong>5.</strong> Lorem Ipsum
            </p>
        </div>
        <div class="gy-4">
            <div class="row px-3 rounded">
                <p>A) Lorem Ipsum.
                </p>
                <div class="row">
                    <div class="col-lg-3 mx-auto">
                        <div class="list-group list-group-radio d-grid gap-2 border-0">
                            <div class="position-relative">
                                <input class="form-check-input position-absolute top-50 end-0 me-3 fs-5"
                                    type="radio" name="1-ex-multi-tf-A" id="1-ex-multi-tf-1" value="">
                                <label class="list-group-item py-3 pe-5" for="1-ex-multi-tf-1">
                                    <strong class="fw-semibold">Verdadeira</strong>
                                </label>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-3 mx-auto">
                        <div class="list-group list-group-radio d-grid gap-2 border-0">
                            <div class="position-relative">
                                <input class="form-check-input position-absolute top-50 end-0 me-3 fs-5"
                                    type="radio" name="1-ex-multi-tf-A" id="1-ex-multi-tf-2" value="">
                                <label class="list-group-item py-3 pe-5" for="1-ex-multi-tf-2">
                                    <strong class="fw-semibold">Falsa</strong>
                                </label>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <hr class="center">
            <br>
            <div class="row px-3 rounded">
                <p>B) Lorem Ipsum.
                </p>
                <div class="row">
                    <div class="col-lg-3 mx-auto">
                        <div class="list-group list-group-radio d-grid gap-2 border-0">
                            <div class="position-relative">
                                <input class="form-check-input position-absolute top-50 end-0 me-3 fs-5"
                                    type="radio" name="1-ex-multi-tf-B" id="1-ex-multi-tf-3" value="">
                                <label class="list-group-item py-3 pe-5" for="1-ex-multi-tf-3">
                                    <strong class="fw-semibold">Verdadeira</strong>
                                </label>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-3 mx-auto">
                        <div class="list-group list-group-radio d-grid gap-2 border-0">
                            <div class="position-relative">
                                <input class="form-check-input position-absolute top-50 end-0 me-3 fs-5"
                                    type="radio" name="1-ex-multi-tf-B" id="1-ex-multi-tf-4" value="">
                                <label class="list-group-item py-3 pe-5" for="1-ex-multi-tf-4">
                                    <strong class="fw-semibold">Falsa</strong>
                                </label>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <hr class="center">
            <div class="row px-3 rounded">
                <p>C) Lorem Ipsum.
                </p>
                <div class="row mx-auto">
                    <div class="col-lg-3 mx-auto">
                        <div class="list-group list-group-radio d-grid gap-2 border-0">
                            <div class="position-relative">
                                <input class="form-check-input position-absolute top-50 end-0 me-3 fs-5"
                                    type="radio" name="1-ex-multi-tf-C" id="1-ex-multi-tf-5" value="">
                                <label class="list-group-item py-3 pe-5" for="1-ex-multi-tf-5">
                                    <strong class="fw-semibold">Verdadeira</strong>
                                </label>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-3 mx-auto">
                        <div class="list-group list-group-radio d-grid gap-2 border-0">
                            <div class="position-relative">
                                <input class="form-check-input position-absolute top-50 end-0 me-3 fs-5"
                                    type="radio" name="1-ex-multi-tf-C" id="1-ex-multi-tf-6" value="">
                                <label class="list-group-item py-3 pe-5" for="1-ex-multi-tf-6">
                                    <strong class="fw-semibold">Falsa</strong>
                                </label>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <br>
        <div class="collapse mt-20" id="collapse-multi-tf-ex1-seleciona">
            <div class="card mt-20 shadow">
                <div class="card-header">
                    <div class="card-title d-inline-flex align-baseline">
                        <i class="bi bi-exclamation-circle"></i>
                        <span class="ms-1">
                            Atenção!
                        </span>
                    </div>
                </div>
                <div class="card-body   p-3">
                    <p>Selecione todas as alternativas do exercício.</p>
                </div>
            </div>
        </div>
        <div class="collapse mt-20" id="collapse-multi-tf-ex1-certo">
            <div class="card mt-20 shadow">
                <div class="card-header">
                    <div class="card-title d-inline-flex align-baseline">
                        <i class="bi bi-check-circle"></i><span class="ms-1">Parabéns!
                            Resposta
                            correta.</span>
                    </div>
                </div>
                <div class="card-body p-3">
                    <p>
                        Lorem Ipsum
                    </p>
                </div>
            </div>
        </div>
        <div class="collapse mt-20" id="collapse-multi-tf-ex1-tentativa1">
            <div class="card mt-20 shadow">
                <div class="card-header">
                    <div class="card-title d-inline-flex align-baseline">
                        <i class="bi bi-x-circle"></i> <span class="ms-1">Resposta
                            incorreta.</span>
                    </div>
                </div>
                <div class="card-body p-3">
                    <p>Tente outra vez! Lorem Ipsum
                    </p>
                </div>
            </div>
        </div>
        <div class="collapse mt-20" id="collapse-multi-tf-ex1-errada">
            <div class="card mt-20 shadow">
                <div class="card-header">
                    <div class="card-title d-inline-flex align-baseline">
                        <i class="bi bi-x-circle"></i> <span class="ms-1">Resposta
                            incorreta.</span>
                    </div>
                </div>
                <div class="card-body p-3">
                    <p>
                        Lorem Ipsum
                    </p>
                </div>
            </div>
        </div>
        <div class="gy-4 m-2" id="vr-button1multi-tf">
            <div class="row">
                <div class="d-grid gap-2 col-md-3 mx-auto p-3">
                    <button class="btn border" onClick="RespostaTrueOrFalse1();"><span>Verificar
                            Resposta</span></button>
                </div>
            </div>
        </div>
    </div>
</div>

```

## Modal
```html
<div class="d-grid gap-2">
    <button class="uk-button uk-button-default " type="button"
        uk-toggle="target: #modal-close-default">
        Modal - Padrão Simples
    </button>
</div>
<div id="modal-close-default" uk-modal>
    <div class="uk-modal-dialog uk-modal-body">
        <button class="uk-modal-close-default" type="button" uk-close></button>
        <h2 class="uk-modal-title">Lorem Ipsum</h2>
        <p>
            Lorem Ipsum
        </p>
    </div>
</div>
```

## Nav tabs
```html
<nav>
    <div class="nav nav-tabs mb-3" id="nav-tab" role="tablist">
        <button class="nav-link active" id="nav-1-tab" data-bs-toggle="tab"
            data-bs-target="#nav-1" type="button" role="tab" aria-controls="nav-1"
            aria-selected="false">Lorem Ipsum 1</button>
        <button class="nav-link" id="nav-2-tab" data-bs-toggle="tab"
            data-bs-target="#nav-2" type="button" role="tab" aria-controls="nav-2"
            aria-selected="false">Lorem Ipsum 2</button>
        <button class="nav-link" id="nav-3-tab" data-bs-toggle="tab"
            data-bs-target="#nav-3" type="button" role="tab" aria-controls="nav-3"
            aria-selected="false">Lorem Ipsum 3</button>
    </div>
</nav>
<div class="tab-content" id="nav-tabContent">
    <div class="tab-pane fade show active" id="nav-1" role="tabpanel"
        aria-labelledby="nav-1-tab">
        <p>
            Lorem Ipsum 1
        </p>
    </div>
    <div class="tab-pane fade" id="nav-2" role="tabpanel" aria-labelledby="nav-2-tab">
        <p>
            Lorem Ipsum 2
        </p>
    </div>
    <div class="tab-pane fade" id="nav-3" role="tabpanel" aria-labelledby="nav-3-tab">
        <p>
            Lorem Ipsum 3
        </p>
    </div>
</div>
```

## Nav tabs left
```html
<div uk-grid>
    <div class="uk-width-auto@m">
        <ul class="uk-tab-left"
            uk-tab="connect: #component-tab-left; animation: uk-animation-fade">
            <li><a href="#">Lorem Ipsum 1</a></li>
            <li><a href="#">Lorem Ipsum 2</a></li>
            <li><a href="#">Lorem Ipsum 3</a></li>
        </ul>
    </div>
    <div class="uk-width-expand@m">
        <ul id="component-tab-left" class="uk-switcher">
            <li>
                Lorem Ipsum 1
            </li>
            <li>
                Lorem Ipsum 2
            </li>
             <li>
                Lorem Ipsum 3
            </li>
        </ul>
    </div>
</div>
```


## Parallax moving
```html
<div class="row py-3">
    <div class="uk-height-large uk-background-cover uk-light uk-flex" uk-parallax="bgy: -200"
        style="background-image: url('#imagem');">
        <img src="" alt="" srcset="">
        <h1 class="uk-width-1-2@m uk-text-center uk-margin-auto uk-margin-auto-vertical"
            uk-parallax="y: 100,0">
             Lorem Ipsum
        </h1>
        <p class="uk-width-1-2@m uk-text-center uk-margin-auto uk-margin-auto-vertical"
            uk-parallax="y: 100,0">
            Lorem Ipsum
        </p>
    </div>
</div>
```

## Parallax text 
```html
<div class="uk-height-large uk-background-cover uk-overflow-hidden uk-light uk-flex" style="background: linear-gradient(90deg, #2682ae, #bddcbb, #f4a7bf);background-size: 400% 400%;
        animation: gradient 25s ease infinite;height:auto">
    <div class="p-2 uk-text-center uk-margin-auto uk-margin-auto-vertical">
        <div class="uk-text-center uk-margin-auto uk-margin-auto-vertical">
            <div class="card" uk-parallax="opacity: 0,1; y: 100,0; scale: 0.5,1; end: 50vh + 50%;">
                <div class="card-body ">
                    <h3>Lorem Ipsum</h3>
                    <p>Lorem Ipsum</p>
                </div>
            </div>
            <div class="card  mb-2 mt-2"
                uk-parallax="opacity: 0,1; y: 100,0; scale: 0.5,1; end: 50vh + 50%;">
                <div class="card-body ">
                     <h3>Lorem Ipsum</h3>
                    <p>Lorem Ipsum</p>
                </div>
            </div>
            <div class="card" uk-parallax="opacity: 0,1; y: 100,0; scale: 0.5,1; end: 50vh + 50%;">
                <div class="card-body ">
                    <h3>Lorem Ipsum</h3>
                    <p>Lorem Ipsum</p>
                </div>
            </div>
        </div>
    </div>
</div>
```

## Slider
```html
<div uk-slider>
    <div class="uk-position-relative">
        <div class="uk-slider-container uk-light">
            <ul class="uk-slider-items ">
                <li>
                    <img class="img-fluid" src="Layout/Template/img/1.png" alt="">

                </li>
                <li>
                    <img src="Layout/Template/img/2.png" alt="">

                </li>
                <li>
                    <img src="Layout/Template/img/3.png" alt="">

                </li>

            </ul>
        </div>
        <div class="uk-hidden@s uk-light">
            <a class="uk-position-center-left uk-position-small" href="#"
                uk-slidenav-previous uk-slider-item="previous"></a>
            <a class="uk-position-center-right uk-position-small" href="#" uk-slidenav-next
                uk-slider-item="next"></a>
        </div>
        <div class="uk-visible@s">
            <a class="uk-position-center-left-out uk-position-small" href="#"
                uk-slidenav-previous uk-slider-item="previous"></a>
            <a class="uk-position-center-right-out uk-position-small" href="#"
                uk-slidenav-next uk-slider-item="next"></a>
        </div>
    </div>
    <ul class="uk-slider-nav uk-dotnav uk-flex-center uk-margin"></ul>
</div>
```

## Video youtube
```html
<div class="ratio ratio-16x9 ">
    <iframe class="rounded" src="https://www.youtube.com/embed/#"
        title="YouTube video" allowfullscreen>
    </iframe>
</div>
```

## Video interno 
```html
<video class="rounded" src="#" controlslist="nodownload" controls>
</video>
```
## Video youtube charpters
```html
<div id="player1" class="py-5">
```
