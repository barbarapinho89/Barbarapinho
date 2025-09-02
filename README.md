# Barbarapinho
Evento 
import java.time.LocalDateTime;
import java.time.format.DateTimeFormatter;
import java.util.*;

public class Evento {
    private final String id;
    private final String nome;
    private final String endereco;
    private final CategoriaEvento categoria;
    private final LocalDateTime dataHora;
    private final int duracaoMin;
    private final String descricao;
    private final List<String> participantes = new ArrayList<>();

   

