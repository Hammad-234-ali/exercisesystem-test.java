# exercisesystem-test.java
import org.junit.jupiter.api.Test;
import static org.junit.jupiter.api.Assertions.*;

public class ExerciseSystemTest {
    @Test
    public void testSuggestExercises() {
        ExerciseSystem exerciseSystem = new ExerciseSystem();
        exerciseSystem.suggestExercises();
    }
}
