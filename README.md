# psi-avaliacao2-hugley

1- 
Rotas concretas estavam fora do controller


2-


3-
Para conseguir rodar as rotas dos blueprints em arquivos diferentes
@servicos_bp.route("/servicos")
def listar_servicos():
    return render_template("catalog.index.html", servicos=models.servicos)

