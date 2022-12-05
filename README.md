4)
class Equipamento {
    private int voltagem;
    private double memoria;
}

5)
public class Computador extends Equipamento{
}

6)
public class Equipamento {
    private int voltagem;
    private double memoria;
    
    public int getVoltagem(){
        return this.voltagem;
    }
    
    public void setVoltagem(int voltagem){
        this.voltagem = voltagem;
    }
    
    public double getMemoria(){
        return this.memoria;
    }
    
    public void setMemoria(int memoria){
        this.memoria = memoria;
    }
}
