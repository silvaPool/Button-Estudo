Eu me deparei com este efeito e o que me chamou a atenção foi esta notação:
.cards .card:hover {
    transform: scale(1.1, 1.1);
}

.cards:hover > .card:not(:hover) {
    filter: blur(10px);
    transform: scale(0.9, 0.9);
}

Quando o mouse estiver sobre um card os outros dois ficarão com a scale menor e com um filter. Isso é muito interessante, pois vejo inúmeras possibilidades de aplicar isso em projeto real.
