# Ch03 · Multidimensional Grids and Data

> **Reading date:** 2026-06-13  
> **Status:** 🔄 In Progress / ✅ Done

---

## Key Concepts

The core idea of this chapter in one or two sentences. What problem does it solve,
and what is the main mechanism?

---

## Notes

### Section title

Your notes here. Explain in your own words — don't copy the book.

$$
\text{global\_index} = blockIdx.x \times blockDim.x + threadIdx.x
$$

### Another section

!!! note "Important"
    Something worth flagging — a non-obvious detail, a common mistake, etc.

---

## Code

```cuda
// Minimal working example that captures the chapter's core idea
__global__ void kernel(float* d_out, float* d_in, int N) {
    int i = blockIdx.x * blockDim.x + threadIdx.x;
    if (i < N) d_out[i] = d_in[i];
}
```

---

## My Questions

- Something I didn't fully understand
- Something I want to verify by running code

---

## Summary

Three to five bullet points. What should you still remember six months from now?

- 
- 
-