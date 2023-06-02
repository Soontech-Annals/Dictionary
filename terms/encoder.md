# Encoder
(noun)

## 1. A device that, for a given item, emits a redstone code corresponding to an item type

| IO  | Type | Description                                       |
|-----|------|---------------------------------------------------|
| In  | Item | Item to be encoded                                |
| Out | Code | Redstone code corresponding to item type of input |

This device used to be called a *decoder* because of [PallaPalla's video](https://youtu.be/ksfBEgLSpA0) on the concept. It has since been renamed to be called an *encoder* because it generates redstone-based codes. The consensus is that the redstone-based signals are better described as codes than the input items themselves (See definition 2).

The encoding operation is a [surjective](https://en.wikipedia.org/wiki/Surjective_function) function denoted as $E: I \to C$ where $I$ is the set of item types in the game, and $C$ is the set of codes that can be output by the encoder. Note that $|C| < |I|$ if multiple items map to the same code (potentially for an MIS).

Most encoders employ a numeral coding scheme to reduce the amount of unique symbols required to convey the code. The simplest to implement is binary (base 2), but other arrangements are possible.

Using these techniques, encoders in minecraft can be very small while being able to emit many different codes.

## 2. A device that [encodes](https://www.merriam-webster.com/dictionary/encode)

This is a more general definition of an encoder. In the context of encoded technologies, different things may be designated as "code" depending on use-case. It is even possible for an encoder to encode items with other items! For the sake of everyone's sanity, please don't use this definition without context.
