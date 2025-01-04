This repository demonstrates a common bug in Rust related to using raw pointers with vectors.  The `bug.rs` file contains code that attempts to modify a vector's element through a raw pointer after the vector has potentially been reallocated. This results in undefined behavior. The `bugSolution.rs` demonstrates a safer approach using safe Rust methods.