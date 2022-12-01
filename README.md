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
    
    public double getMemoria(){
        return this.memoria;
    }
}
