#B.1 Diagnostics <assert.h>

Name | C Version | Optional | Rust libc
-|-|-|-
`NDEBUG` | C90 | | N/A
`static_assert` | C11 | | N/A
`void assert(scalar expression);` | C90 | | N/A

#B.2 Complex <complex.h>

Name | C Version | Optional | Rust libc
-|-|-|-
`_ _STDC_NO_COMPLEX_ _` | C11 | `_ _STDC_NO_COMPLEX_ _` | N/A
`imaginary` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`complex` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`_Imaginary_I` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`_Complex_I` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`I` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double complex cacos(double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float complex cacosf(float complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double complex cacosl(long double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double complex casin(double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float complex casinf(float complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double complex casinl(long double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double complex catan(double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float complex catanf(float complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double complex catanl(long double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double complex ccos(double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float complex ccosf(float complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double complex ccosl(long double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double complex csin(double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float complex csinf(float complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double complex csinl(long double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double complex ctan(double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float complex ctanf(float complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double complex ctanl(long double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double complex cacosh(double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float complex cacoshf(float complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double complex cacoshl(long double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double complex casinh(double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float complex casinhf(float complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double complex casinhl(long double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double complex catanh(double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float complex catanhf(float complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double complex catanhl(long double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double complex ccosh(double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float complex ccoshf(float complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double complex ccoshl(long double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double complex csinh(double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float complex csinhf(float complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double complex csinhl(long double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double complex ctanh(double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float complex ctanhf(float complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double complex ctanhl(long double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double complex cexp(double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float complex cexpf(float complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double complex cexpl(long double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double complex clog(double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float complex clogf(float complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double complex clogl(long double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double cabs(double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float cabsf(float complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double cabsl(long double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double complex cpow(double complex x, double complex y);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float complex cpowf(float complex x, float complex y);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double complex cpowl(long double complex x, long double complex y);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double complex csqrt(double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float complex csqrtf(float complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double complex csqrtl(long double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double carg(double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float cargf(float complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double cargl(long double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double cimag(double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float cimagf(float complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double cimagl(long double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double complex CMPLX(double x, double y);` | C11 | `!_ _STDC_NO_COMPLEX_ _` | No
`float complex CMPLXF(float x, float y);` | C11 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double complex CMPLXL(long double x, long double y);` | C11 | `!_ _STDC_NO_COMPLEX_ _` | No
`double complex conj(double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float complex conjf(float complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double complex conjl(long double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double complex cproj(double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float complex cprojf(float complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double complex cprojl(long double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`double creal(double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`float crealf(float complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No
`long double creall(long double complex z);` | C99 | `!_ _STDC_NO_COMPLEX_ _` | No

#B.3 Character handling <ctype.h>

Name | C Version | Optional | Rust libc
-|-|-|-
`int isalnum(int c);` | C90 | | Yes
`int isalpha(int c);` | C90 | | Yes
`int isblank(int c);` | C99 | | No
`int iscntrl(int c);` | C90 | | Yes
`int isdigit(int c);` | C90 | | Yes
`int isgraph(int c);` | C90 | | Yes
`int islower(int c);` | C90 | | Yes
`int isprint(int c);` | C90 | | Yes
`int ispunct(int c);` | C90 | | Yes
`int isspace(int c);` | C90 | | Yes
`int isupper(int c);` | C90 | | Yes
`int isxdigit(int c);` | C90 | | Yes
`int tolower(int c);` | C90 | | Yes
`int toupper(int c);` | C90 | | Yes

#B.4 Errors <errno.h>

Name | C Version | Optional | Rust libc
-|-|-|-
`EDOM` | C90 | | Yes
`EILSEQ` | C99 | | Yes
`ERANGE` | C90 | | Yes
`errno` | C90 | | No
`_ _STDC_WANT_LIB_EXT1_ _` | C11 | `_ _STDC_WANT_LIB_EXT1_ _` | N/A
`errno_t` | C11 | `_ _STDC_WANT_LIB_EXT1_ _` | No

#B.5 Floating-point environment <fenv.h>

Name | C Version | Optional | Rust libc
-|-|-|-
`fenv_t` | C99 | | No
`FE_OVERFLOW` | C99 | | No
`FE_TOWARDZERO` | C99 | | No
`fexcept_t` | C99 | | No
`FE_UNDERFLOW` | C99 | | No
`FE_UPWARD` | C99 | | No
`FE_DIVBYZERO` | C99 | | No
`FE_ALL_EXCEPT` | C99 | | No
`FE_DFL_ENV` | C99 | | No
`FE_INEXACT` | C99 | | No
`FE_DOWNWARD` | C99 | | No
`FE_INVALID` | C99 | | No
`FE_TONEAREST` | C99 | | No
`int feclearexcept(int excepts);` | C99 | | No
`int fegetexceptflag(fexcept_t *flagp, int excepts);` | C99 | | No
`int feraiseexcept(int excepts);` | C99 | | No
`int fesetexceptflag(const fexcept_t *flagp, int excepts);` | C99 | | No
`int fetestexcept(int excepts);` | C99 | | No
`int fegetround(void);` | C99 | | No
`int fesetround(int round);` | C99 | | No
`int fegetenv(fenv_t *envp);` | C99 | | No
`int feholdexcept(fenv_t *envp);` | C99 | | No
`int fesetenv(const fenv_t *envp);` | C99 | | No
`int feupdateenv(const fenv_t *envp);` | C99 | | No

#B.6 Characteristics of floating types <float.h>

Name | C Version | Optional | Rust libc
-|-|-|-
`FLT_ROUNDS` | C90 | | No
`DBL_DIG` | C90 | | No
`FLT_MAX` | C90 | | No
`FLT_EVAL_METHOD` | C99 | | No
`LDBL_DIG` | C90 | | No
`DBL_MAX` | C90 | | No
`FLT_HAS_SUBNORM` | C11 | | No
`FLT_MIN_EXP` | C90 | | No
`LDBL_MAX` | C90 | | No
`DBL_HAS_SUBNORM` | C11 | | No
`DBL_MIN_EXP` | C90 | | No
`FLT_EPSILON` | C90 | | No
`LDBL_HAS_SUBNORM` | C11 | | No
`LDBL_MIN_EXP` | C90 | | No
`DBL_EPSILON` | C90 | | No
`FLT_RADIX` | C90 | | No
`FLT_MIN_10_EXP` | C90 | | No
`LDBL_EPSILON` | C90 | | No
`FLT_MANT_DIG` | C90 | | No
`DBL_MIN_10_EXP` | C90 | | No
`FLT_MIN` | C90 | | No
`DBL_MANT_DIG` | C90 | | No
`LDBL_MIN_10_EXP` | C90 | | No
`DBL_MIN` | C90 | | No
`LDBL_MANT_DIG` | C90 | | No
`FLT_MAX_EXP` | C90 | | No
`LDBL_MIN` | C90 | | No
`FLT_DECIMAL_DIG` | C90 | | No
`DBL_MAX_EXP` | C90 | | No
`FLT_TRUE_MIN` | C90 | | No
`DBL_DECIMAL_DIG` | C90 | | No
`LDBL_MAX_EXP` | C90 | | No
`DBL_TRUE_MIN` | C90 | | No
`LDBL_DECIMAL_DIG` | C90 | | No
`FLT_MAX_10_EXP` | C90 | | No
`LDBL_TRUE_MIN` | C90 | | No
`DECIMAL_DIG` | C99 | | No
`DBL_MAX_10_EXP` | C90 | | No
`FLT_DIG` | C90 | | No
`LDBL_MAX_10_EXP` | C90 | | No

#B.7 Format conversion of integer types <inttypes.h>

Name | C Version | Optional | Rust libc
-|-|-|-
`imaxdiv_t` | C99 | | No
`PRIdN` | C99 | | N/A
`PRIdLEASTN` | C99 | | N/A
`PRIdFASTN` | C99 | | N/A
`PRIdMAX` | C99 | | N/A
`PRIdPTR` | C99 | | N/A
`PRIiN` | C99 | | N/A
`PRIiLEASTN` | C99 | | N/A
`PRIiFASTN` | C99 | | N/A
`PRIiMAX` | C99 | | N/A
`PRIiPTR` | C99 | | N/A
`PRIoN` | C99 | | N/A
`PRIoLEASTN` | C99 | | N/A
`PRIoFASTN` | C99 | | N/A
`PRIoMAX` | C99 | | N/A
`PRIoPTR` | C99 | | N/A
`PRIuN` | C99 | | N/A
`PRIuLEASTN` | C99 | | N/A
`PRIuFASTN` | C99 | | N/A
`PRIuMAX` | C99 | | N/A
`PRIuPTR` | C99 | | N/A
`PRIxN` | C99 | | N/A
`PRIxLEASTN` | C99 | | N/A
`PRIxFASTN` | C99 | | N/A
`PRIxMAX` | C99 | | N/A
`PRIxPTR` | C99 | | N/A
`PRIXN` | C99 | | N/A
`PRIXLEASTN` | C99 | | N/A
`PRIXFASTN` | C99 | | N/A
`PRIXMAX` | C99 | | N/A
`PRIXPTR` | C99 | | N/A
`SCNdN` | C99 | | N/A
`SCNdLEASTN` | C99 | | N/A
`SCNdFASTN` | C99 | | N/A
`SCNdMAX` | C99 | | N/A
`SCNdPTR` | C99 | | N/A
`SCNiN` | C99 | | N/A
`SCNiLEASTN` | C99 | | N/A
`SCNiFASTN` | C99 | | N/A
`SCNiMAX` | C99 | | N/A
`SCNiPTR` | C99 | | N/A
`SCNoN` | C99 | | N/A
`SCNoLEASTN` | C99 | | N/A
`SCNoFASTN` | C99 | | N/A
`SCNoMAX` | C99 | | N/A
`SCNoPTR` | C99 | | N/A
`SCNuN` | C99 | | N/A
`SCNuLEASTN` | C99 | | N/A
`SCNuFASTN` | C99 | | N/A
`SCNuMAX` | C99 | | N/A
`SCNuPTR` | C99 | | N/A
`SCNxN` | C99 | | N/A
`SCNxLEASTN` | C99 | | N/A
`SCNxFASTN` | C99 | | N/A
`SCNxMAX` | C99 | | N/A
`SCNxPTR` | C99 | | N/A
`intmax_t imaxabs(intmax_t j);` | C99 | | No
`imaxdiv_t imaxdiv(intmax_t numer, intmax_t denom);` | C99 | | No
`intmax_t strtoimax(const char * restrict nptr, char ** restrict endptr, int base);` | C99 | | No
`uintmax_t strtoumax(const char * restrict nptr, char ** restrict endptr, int base);` | C99 | | No
`intmax_t wcstoimax(const wchar_t * restrict nptr, wchar_t ** restrict endptr, int base);` | C99 | | No
`uintmax_t wcstoumax(const wchar_t * restrict nptr, wchar_t ** restrict endptr, int base);` | C99 | | No

#B.8 Alternative spellings <iso646.h>

Name | C Version | Optional | Rust libc
-|-|-|-
`and` | C95 | | N/A
`bitor` | C95 | | N/A
`not_eq` | C95 | | N/A
`xor` | C95 | | N/A
`and_eq` | C95 | | N/A
`compl` | C95 | | N/A
`or` | C95 | | N/A
`xor_eq` | C95 | | N/A
`bitand` | C95 | | N/A
`not` | C95 | | N/A
`or_eq` | C95 | | N/A

#B.9 Sizes of integer types <limits.h>

Name | C Version | Optional | Rust libc
-|-|-|-
`CHAR_BIT` | C90 | | No
`CHAR_MAX` | C90 | | No
`INT_MIN` | C90 | | No
`ULONG_MAX` | C90 | | No
`SCHAR_MIN` | C90 | | No
`MB_LEN_MAX` | C90 | | No
`INT_MAX` | C90 | | No
`LLONG_MIN` | C90 | | No
`SCHAR_MAX` | C90 | | No
`SHRT_MIN` | C90 | | No
`UINT_MAX` | C90 | | No
`LLONG_MAX` | C90 | | No
`UCHAR_MAX` | C90 | | No
`SHRT_MAX` | C90 | | No
`LONG_MIN` | C90 | | No
`ULLONG_MAX` | C90 | | No
`CHAR_MIN` | C90 | | No
`USHRT_MAX` | C90 | | No
`LONG_MAX` | C90 | | No

#B.10 Localization <locale.h>

Name | C Version | Optional | Rust libc
-|-|-|-
`struct lconv` | C90 | | No
`LC_ALL` | C90 | | No
`LC_CTYPE` | C90 | | No
`LC_NUMERIC` | C90 | | No
`NULL` | C90 | | No
`LC_COLLATE` | C90 | | No
`LC_MONETARY` | C90 | | No
`LC_TIME` | C90 | | No
`char *setlocale(int category, const char *locale);` | C90 | | No
`struct lconv *localeconv(void);` | C90 | | No

#B.11 Mathematics <math.h>

Name | C Version | Optional | Rust libc
-|-|-|-
`float_t
`FP_INFINITE
`FP_FAST_FMAL
`double_t
`FP_NAN
`FP_ILOGB0
`HUGE_VAL
`FP_NORMAL
`FP_ILOGBNAN
`HUGE_VALF
`FP_SUBNORMAL
`MATH_ERRNO
`HUGE_VALL
`FP_ZERO
`MATH_ERREXCEPT
`INFINITY
`FP_FAST_FMA
`math_errhandling
`NAN
`FP_FAST_FMAF
`int fpclassify(real-floating x);
`int isfinite(real-floating x);
`int isinf(real-floating x);
`int isnan(real-floating x);
`int isnormal(real-floating x);
`int signbit(real-floating x);
`double acos(double x);
`float acosf(float x);
`long double acosl(long double x);
`double asin(double x);
`float asinf(float x);
`long double asinl(long double x);
`double atan(double x);
`float atanf(float x);
`long double atanl(long double x);
`double atan2(double y, double x);
`float atan2f(float y, float x);
`long double atan2l(long double y, long double x);
`double cos(double x);
`float cosf(float x);
`long double cosl(long double x);
`double sin(double x);
`float sinf(float x);
`long double sinl(long double x);
`double tan(double x);
`float tanf(float x);
`long double tanl(long double x);
`double acosh(double x);
`float acoshf(float x);
`long double acoshl(long double x);
`double asinh(double x);
`float asinhf(float x);
`long double asinhl(long double x);
`double atanh(double x);
`float atanhf(float x);
`long double atanhl(long double x);
`double cosh(double x);
`float coshf(float x);
`long double coshl(long double x);
`double sinh(double x);
`float sinhf(float x);
`long double sinhl(long double x);
`double tanh(double x);
`float tanhf(float x);
`long double tanhl(long double x);
`double exp(double x);
`float expf(float x);
`long double expl(long double x);
`double exp2(double x);
`float exp2f(float x);
`long double exp2l(long double x);
`double expm1(double x);
`float expm1f(float x);
`long double expm1l(long double x);
`double frexp(double value, int *exp);
`float frexpf(float value, int *exp);
`long double frexpl(long double value, int *exp);
`int ilogb(double x);
`int ilogbf(float x);
`int ilogbl(long double x);
`double ldexp(double x, int exp);
`float ldexpf(float x, int exp);
`long double ldexpl(long double x, int exp);
`double log(double x);
`float logf(float x);
`long double logl(long double x);
`double log10(double x);
`float log10f(float x);
`long double log10l(long double x);
`double log1p(double x);
`float log1pf(float x);
`long double log1pl(long double x);
`double log2(double x);
`float log2f(float x);
`long double log2l(long double x);
`double logb(double x);
`float logbf(float x);
`long double logbl(long double x);
`double modf(double value, double *iptr);
`float modff(float value, float *iptr);
`long double modfl(long double value, long double *iptr);
`double scalbn(double x, int n);
`float scalbnf(float x, int n);
`long double scalbnl(long double x, int n);
`double scalbln(double x, long int n);
`float scalblnf(float x, long int n);
`long double scalblnl(long double x, long int n);
`double cbrt(double x);
`float cbrtf(float x);
`long double cbrtl(long double x);
`double fabs(double x);
`float fabsf(float x);
`long double fabsl(long double x);
`double hypot(double x, double y);
`float hypotf(float x, float y);
`long double hypotl(long double x, long double y);
`double pow(double x, double y);
`float powf(float x, float y);
`long double powl(long double x, long double y);
`double sqrt(double x);
`float sqrtf(float x);
`long double sqrtl(long double x);
`double erf(double x);
`float erff(float x);
`long double erfl(long double x);
`double erfc(double x);
`float erfcf(float x);
`long double erfcl(long double x);
`double lgamma(double x);
`float lgammaf(float x);
`long double lgammal(long double x);
`double tgamma(double x);
`float tgammaf(float x);
`long double tgammal(long double x);
`double ceil(double x);
`float ceilf(float x);
`long double ceill(long double x);
`double floor(double x);
`float floorf(float x);
`long double floorl(long double x);
`double nearbyint(double x);
`float nearbyintf(float x);
`long double nearbyintl(long double x);
`double rint(double x);
`float rintf(float x);
`long double rintl(long double x);
`long int lrint(double x);
`long int lrintf(float x);
`long int lrintl(long double x);
`long long int llrint(double x);
`long long int llrintf(float x);
`long long int llrintl(long double x);
`double round(double x);
`float roundf(float x);
`long double roundl(long double x);
`long int lround(double x);
`long int lroundf(float x);
`long int lroundl(long double x);
`long long int llround(double x);
`long long int llroundf(float x);
`long long int llroundl(long double x);
`double trunc(double x);
`float truncf(float x);
`long double truncl(long double x);
`double fmod(double x, double y);
`float fmodf(float x, float y);
`long double fmodl(long double x, long double y);
`double remainder(double x, double y);
`float remainderf(float x, float y);
`long double remainderl(long double x, long double y);
`double remquo(double x, double y, int *quo);
`float remquof(float x, float y, int *quo);
`long double remquol(long double x, long double y, int *quo);
`double copysign(double x, double y);
`float copysignf(float x, float y);
`long double copysignl(long double x, long double y);
`double nan(const char *tagp);
`float nanf(const char *tagp);
`long double nanl(const char *tagp);
`double nextafter(double x, double y);
`float nextafterf(float x, float y);
`long double nextafterl(long double x, long double y);
`double nexttoward(double x, long double y);
`float nexttowardf(float x, long double y);
`long double nexttowardl(long double x, long double y);
`double fdim(double x, double y);
`float fdimf(float x, float y);
`long double fdiml(long double x, long double y);
`double fmax(double x, double y);
`float fmaxf(float x, float y);
`long double fmaxl(long double x, long double y);
`double fmin(double x, double y);
`float fminf(float x, float y);
`long double fminl(long double x, long double y);
`double fma(double x, double y, double z);
`float fmaf(float x, float y, float z);
`long double fmal(long double x, long double y, long double z);
`int isgreater(real-floating x, real-floating y);
`int isgreaterequal(real-floating x, real-floating y);
`int isless(real-floating x, real-floating y);
`int islessequal(real-floating x, real-floating y);
`int islessgreater(real-floating x, real-floating y);
`int isunordered(real-floating x, real-floating y);

#B.12 Nonlocal jumps <setjmp.h>

Name | C Version | Optional | Rust libc
-|-|-|-
`jmp_buf` | C90 | | No
`int setjmp(jmp_buf env);` | C90 | | No
`_Noreturn void longjmp(jmp_buf env, int val);` | C90 | | No

#B.13 Signal handling <signal.h>

Name | C Version | Optional | Rust libc
-|-|-|-
`sig_atomic_t` | C90 | | No
`SIG_IGN` | C90 | | Yes
`SIGILL` | C90 | | Yes
`SIGTERM` | C90 | | Yes
`SIG_DFL` | C90 | | No
`SIGABRT` | C90 | | Yes
`SIGINT` | C90 | | Yes
`SIG_ERR` | C90 | | No
`SIGFPE` | C90 | | Yes
`SIGSEGV` | C90 | | Yes
`void (*signal(int sig, void (*func)(int)))(int);` | C90 | | No
`int raise(int sig);` | C90 | | No

#B.14 Alignment <stdalign.h>

Name | C Version | Optional | Rust libc
-|-|-|-
`alignas` | C11 | | N/A
`_ _alignas_is_defined` | C11 | | N/A

#B.15 Variable arguments <stdarg.h>

Name | C Version | Optional | Rust libc
-|-|-|-
`va_list` | C90 | | N/A (Variadic)
`type va_arg(va_list ap, type);` | C90 | | N/A (Variadic)
`void va_copy(va_list dest, va_list src);` | C99 | | N/A (Variadic)
`void va_end(va_list ap);` | C90 | | N/A (Variadic)
`void va_start(va_list ap, parmN);` | C90 | | N/A (Variadic)

#B.16 Atomics <stdatomic.h>

Name | C Version | Optional | Rust libc
-|-|-|-
`ATOMIC_BOOL_LOCK_FREE` | C11 | | No
`ATOMIC_CHAR_LOCK_FREE` | C11 | | No
`ATOMIC_CHAR16_T_LOCK_FREE` | C11 | | No
`ATOMIC_CHAR32_T_LOCK_FREE` | C11 | | No
`ATOMIC_WCHAR_T_LOCK_FREE` | C11 | | No
`ATOMIC_SHORT_LOCK_FREE` | C11 | | No
`ATOMIC_INT_LOCK_FREE` | C11 | | No
`ATOMIC_LONG_LOCK_FREE` | C11 | | No
`ATOMIC_LLONG_LOCK_FREE` | C11 | | No
`ATOMIC_POINTER_LOCK_FREE` | C11 | | No
`ATOMIC_FLAG_INIT` | C11 | | No
`memory_order` | C11 | | No
`atomic_flag` | C11 | | No
`memory_order_relaxed` | C11 | | No
`memory_order_consume` | C11 | | No
`memory_order_acquire` | C11 | | No
`memory_order_release` | C11 | | No
`memory_order_acq_rel` | C11 | | No
`memory_order_seq_cst` | C11 | | No
`atomic_bool` | C11 | | No
`atomic_char` | C11 | | No
`atomic_schar` | C11 | | No
`atomic_uchar` | C11 | | No
`atomic_short` | C11 | | No
`atomic_ushort` | C11 | | No
`atomic_int` | C11 | | No
`atomic_uint` | C11 | | No
`atomic_long` | C11 | | No
`atomic_ulong` | C11 | | No
`atomic_llong` | C11 | | No
`atomic_ullong` | C11 | | No
`atomic_char16_t` | C11 | | No
`atomic_char32_t` | C11 | | No
`atomic_wchar_t` | C11 | | No
`atomic_int_least8_t` | C11 | | No
`atomic_uint_least8_t` | C11 | | No
`atomic_int_least16_t` | C11 | | No
`atomic_uint_least16_t` | C11 | | No
`atomic_int_least32_t` | C11 | | No
`atomic_uint_least32_t` | C11 | | No
`atomic_int_least64_t` | C11 | | No
`atomic_uint_least64_t` | C11 | | No
`atomic_int_fast8_t` | C11 | | No
`atomic_uint_fast8_t` | C11 | | No
`atomic_int_fast16_t` | C11 | | No
`atomic_uint_fast16_t` | C11 | | No
`atomic_int_fast32_t` | C11 | | No
`atomic_uint_fast32_t` | C11 | | No
`atomic_int_fast64_t` | C11 | | No
`atomic_uint_fast64_t` | C11 | | No
`atomic_intptr_t` | C11 | | No
`atomic_uintptr_t` | C11 | | No
`atomic_size_t` | C11 | | No
`atomic_ptrdiff_t` | C11 | | No
`atomic_intmax_t` | C11 | | No
`atomic_uintmax_t` | C11 | | No
`#define ATOMIC_VAR_INIT(C value)` | C11 | | No
`void atomic_init(volatile A *obj, C value);` | C11 | | No
`type kill_dependency(type y);` | C11 | | No
`void atomic_thread_fence(memory_order order);` | C11 | | No
`void atomic_signal_fence(memory_order order);` | C11 | | No
`_Bool atomic_is_lock_free(const volatile A *obj);` | C11 | | No
`void atomic_store(volatile A *object, C desired);` | C11 | | No
`void atomic_store_explicit(volatile A *object, C desired, memory_order order);` | C11 | | No
`C atomic_load(volatile A *object);` | C11 | | No
`C atomic_load_explicit(volatile A *object, memory_order order);` | C11 | | No
`C atomic_exchange(volatile A *object, C desired);` | C11 | | No
`C atomic_exchange_explicit(volatile A *object, C desired, memory_order order);` | C11 | | No
`_Bool atomic_compare_exchange_strong(volatile A *object, C *expected, C desired);` | C11 | | No
`_Bool atomic_compare_exchange_strong_explicit(volatile A *object, C *expected, C desired, memory_order success, memory_order failure);` | C11 | | No
`_Bool atomic_compare_exchange_weak(volatile A *object, C *expected, C desired);` | C11 | | No
`_Bool atomic_compare_exchange_weak_explicit(volatile A *object, C *expected, C desired, memory_order success, memory_order failure);` | C11 | | No
`C atomic_fetch_key(volatile A *object, M operand);` | C11 | | No
`C atomic_fetch_key_explicit(volatile A *object, M operand, memory_order order);` | C11 | | No
`_Bool atomic_flag_test_and_set(volatile atomic_flag *object);` | C11 | | No
`_Bool atomic_flag_test_and_set_explicit(volatile atomic_flag *object, memory_order order);` | C11 | | No
`void atomic_flag_clear(volatile atomic_flag *object);` | C11 | | No
`void atomic_flag_clear_explicit(volatile atomic_flag *object, memory_order order);` | C11 | | No

#B.17 Boolean type and values <stdbool.h>

Name | C Version | Optional | Rust libc
-|-|-|-
`bool`| C99 | | No
`true`| C99 | | No
`false`| C99 | | No
`_ _bool_true_false_are_defined`| C99 | | N/A

#B.18 Common definitions <stddef.h>

Name | C Version | Optional | Rust libc
-|-|-|-
ptrdiff_t
max_align_t
NULL
size_t
wchar_t
offsetof(type, member-designator)
_ _STDC_WANT_LIB_EXT1_ _ | C11
rsize_t | C11

#B.19 Integer types <stdint.h>

Name | Rust libc
-|
intN_t
INT_LEASTN_MIN
PTRDIFF_MAX
uintN_t
INT_LEASTN_MAX
SIG_ATOMIC_MIN
int_leastN_t
UINT_LEASTN_MAX
SIG_ATOMIC_MAX
uint_leastN_t
INT_FASTN_MIN
SIZE_MAX
int_fastN_t
INT_FASTN_MAX
WCHAR_MIN
uint_fastN_t
UINT_FASTN_MAX
WCHAR_MAX
intptr_t
INTPTR_MIN
WINT_MIN
uintptr_t
INTPTR_MAX
WINT_MAX
intmax_t
UINTPTR_MAX
INTN_C(value)
uintmax_t
INTMAX_MIN
UINTN_C(value)
INTN_MIN
INTMAX_MAX
INTMAX_C(value)
INTN_MAX
UINTMAX_MAX
UINTMAX_C(value)
UINTN_MAX
PTRDIFF_MIN
_ _STDC_WANT_LIB_EXT1_ _ | C11
RSIZE_MAX | C11

#B.20 Input/output <stdio.h>

Name | Rust libc
-|
size_t
_IOLBF
FILENAME_MAX
TMP_MAX
FILE
_IONBF
L_tmpnam
stderr
fpos_t
BUFSIZ
SEEK_CUR
stdin
NULL
EOF
SEEK_END
stdout
_IOFBF
FOPEN_MAX
SEEK_SET
int remove(const char *filename);
int rename(const char *old, const char *new);
FILE *tmpfile(void);
char *tmpnam(char *s);
int fclose(FILE *stream);
int fflush(FILE *stream);
FILE *fopen(const char * restrict filename, const char * restrict mode);
FILE *freopen(const char * restrict filename, const char * restrict mode, FILE * restrict stream);
void setbuf(FILE * restrict stream, char * restrict buf);
int setvbuf(FILE * restrict stream, char * restrict buf, int mode, size_t size);
int fprintf(FILE * restrict stream, const char * restrict format, ...);
int fscanf(FILE * restrict stream, const char * restrict format, ...);
int printf(const char * restrict format, ...);
int scanf(const char * restrict format, ...);
int snprintf(char * restrict s, size_t n, const char * restrict format, ...);
int sprintf(char * restrict s, const char * restrict format, ...);
int sscanf(const char * restrict s, const char * restrict format, ...);
int vfprintf(FILE * restrict stream, const char * restrict format, va_list arg);
int vfscanf(FILE * restrict stream, const char * restrict format, va_list arg);
int vprintf(const char * restrict format, va_list arg);
int vscanf(const char * restrict format, va_list arg);
int vsnprintf(char * restrict s, size_t n, const char * restrict format, va_list arg);
int vsprintf(char * restrict s, const char * restrict format, va_list arg);
int vsscanf(const char * restrict s, const char * restrict format, va_list arg);
int fgetc(FILE *stream);
char *fgets(char * restrict s, int n, FILE * restrict stream);
int fputc(int c, FILE *stream);
int fputs(const char * restrict s, FILE * restrict stream);
int getc(FILE *stream);
int getchar(void);
int putc(int c, FILE *stream);
int putchar(int c);
int puts(const char *s);
int ungetc(int c, FILE *stream);
size_t fread(void * restrict ptr, size_t size, size_t nmemb, FILE * restrict stream);
size_t fwrite(const void * restrict ptr, size_t size, size_t nmemb, FILE * restrict stream);
int fgetpos(FILE * restrict stream, fpos_t * restrict pos);
int fseek(FILE *stream, long int offset, int whence);
int fsetpos(FILE *stream, const fpos_t *pos);
long int ftell(FILE *stream);
void rewind(FILE *stream);
void clearerr(FILE *stream);
int feof(FILE *stream);
int ferror(FILE *stream);
void perror(const char *s);
_ _STDC_WANT_LIB_EXT1_ _ | C11
L_tmpnam_s | C11
TMP_MAX_S | C11
errno_t | C11
rsize_t | C11
errno_t tmpfile_s(FILE * restrict * restrict streamptr); | C11
errno_t tmpnam_s(char *s, rsize_t maxsize); | C11
errno_t fopen_s(FILE * restrict * restrict streamptr, const char * restrict filename, const char * restrict mode); | C11
errno_t freopen_s(FILE * restrict * restrict newstreamptr, const char * restrict filename, const char * restrict mode, FILE * restrict stream); | C11
int fprintf_s(FILE * restrict stream, const char * restrict format, ...); | C11
int fscanf_s(FILE * restrict stream, const char * restrict format, ...); | C11
int printf_s(const char * restrict format, ...); | C11
int scanf_s(const char * restrict format, ...); | C11
int snprintf_s(char * restrict s, rsize_t n, const char * restrict format, ...); | C11
int sprintf_s(char * restrict s, rsize_t n, const char * restrict format, ...); | C11
int sscanf_s(const char * restrict s, const char * restrict format, ...); | C11
int vfprintf_s(FILE * restrict stream, const char * restrict format, va_list arg); | C11
int vfscanf_s(FILE * restrict stream, const char * restrict format, va_list arg); | C11
int vprintf_s(const char * restrict format, va_list arg); | C11
int vscanf_s(const char * restrict format, va_list arg); | C11
int vsnprintf_s(char * restrict s, rsize_t n, const char * restrict format, va_list arg); | C11
int vsprintf_s(char * restrict s, rsize_t n, const char * restrict format, va_list arg); | C11
int vsscanf_s(const char * restrict s, const char * restrict format, va_list arg); | C11
char *gets_s(char *s, rsize_t n); | C11

#B.21 General utilities <stdlib.h>

Name | Rust libc
-|
size_t
ldiv_t
EXIT_FAILURE
MB_CUR_MAX
wchar_t
lldiv_t
EXIT_SUCCESS
div_t
NULL
RAND_MAX
double atof(const char *nptr);
int atoi(const char *nptr);
long int atol(const char *nptr);
long long int atoll(const char *nptr);
double strtod(const char * restrict nptr, char ** restrict endptr);
float strtof(const char * restrict nptr, char ** restrict endptr);
long double strtold(const char * restrict nptr, char ** restrict endptr);
long int strtol(const char * restrict nptr, char ** restrict endptr, int base);
long long int strtoll(const char * restrict nptr, char ** restrict endptr, int base);
unsigned long int strtoul(const char * restrict nptr, char ** restrict endptr, int base);
unsigned long long int strtoull(const char * restrict nptr, char ** restrict endptr, int base);
int rand(void);
void srand(unsigned int seed);
void *aligned_alloc(size_t alignment, size_t size);
void *calloc(size_t nmemb, size_t size);
void free(void *ptr);
void *malloc(size_t size);
void *realloc(void *ptr, size_t size);
_Noreturn void abort(void);
int atexit(void (*func)(void));
int at_quick_exit(void (*func)(void));
_Noreturn void exit(int status);
_Noreturn void _Exit(int status);
char *getenv(const char *name);
_Noreturn void quick_exit(int status);
int system(const char *string);
void *bsearch(const void *key, const void *base, size_t nmemb, size_t size, int (*compar)(const void *, const void *));
void qsort(void *base, size_t nmemb, size_t size, int (*compar)(const void *, const void *));
int abs(int j);
long int labs(long int j);
long long int llabs(long long int j);
div_t div(int numer, int denom);
ldiv_t ldiv(long int numer, long int denom);
lldiv_t lldiv(long long int numer, long long int denom);
int mblen(const char *s, size_t n);
int mbtowc(wchar_t * restrict pwc, const char * restrict s, size_t n);
int wctomb(char *s, wchar_t wchar);
size_t mbstowcs(wchar_t * restrict pwcs, const char * restrict s, size_t n);
size_t wcstombs(char * restrict s, const wchar_t * restrict pwcs, size_t n);
_ _STDC_WANT_LIB_EXT1_ _ | C11
errno_t | C11
rsize_t | C11
constraint_handler_t | C11
constraint_handler_t set_constraint_handler_s(constraint_handler_t handler); | C11
void abort_handler_s(const char * restrict msg, void * restrict ptr, errno_t error); | C11
void ignore_handler_s(const char * restrict msg, void * restrict ptr, errno_t error); | C11
errno_t getenv_s(size_t * restrict len, char * restrict value, rsize_t maxsize, const char * restrict name); | C11
void *bsearch_s(const void *key, const void *base, rsize_t nmemb, rsize_t size, int (*compar)(const void *k, const void *y, void *context), void *context); | C11
errno_t qsort_s(void *base, rsize_t nmemb, rsize_t size, int (*compar)(const void *x, const void *y, void *context), void *context); | C11
errno_t wctomb_s(int * restrict status, char * restrict s, rsize_t smax, wchar_t wc); | C11
errno_t mbstowcs_s(size_t * restrict retval, wchar_t * restrict dst, rsize_t dstmax, const char * restrict src, rsize_t len); | C11
errno_t wcstombs_s(size_t * restrict retval, char * restrict dst, rsize_t dstmax, const wchar_t * restrict src, rsize_t len); | C11

#B.22 _Noreturn <stdnoreturn.h>

Name | C Version | Rust libc
-|
noreturn | C11 | N/A

#B.23 String handling <string.h>

Name | Rust libc
-|
size_t
NULL
void *memcpy(void * restrict s1, const void * restrict s2, size_t n);
void *memmove(void *s1, const void *s2, size_t n);
char *strcpy(char * restrict s1, const char * restrict s2);
char *strncpy(char * restrict s1, const char * restrict s2, size_t n);
char *strcat(char * restrict s1, const char * restrict s2);
char *strncat(char * restrict s1, const char * restrict s2, size_t n);
int memcmp(const void *s1, const void *s2, size_t n);
int strcmp(const char *s1, const char *s2);
int strcoll(const char *s1, const char *s2);
int strncmp(const char *s1, const char *s2, size_t n);
size_t strxfrm(char * restrict s1, const char * restrict s2, size_t n);
void *memchr(const void *s, int c, size_t n);
char *strchr(const char *s, int c);
size_t strcspn(const char *s1, const char *s2);
char *strpbrk(const char *s1, const char *s2);
char *strrchr(const char *s, int c);
size_t strspn(const char *s1, const char *s2);
char *strstr(const char *s1, const char *s2);
char *strtok(char * restrict s1, const char * restrict s2);
void *memset(void *s, int c, size_t n);
char *strerror(int errnum);
size_t strlen(const char *s);
_ _STDC_WANT_LIB_EXT1_ _ | C11
errno_t | C11
rsize_t | C11
errno_t memcpy_s(void * restrict s1, rsize_t s1max, const void * restrict s2, rsize_t n); | C11
errno_t memmove_s(void *s1, rsize_t s1max, const void *s2, rsize_t n); | C11
errno_t strcpy_s(char * restrict s1, rsize_t s1max, const char * restrict s2); | C11
errno_t strncpy_s(char * restrict s1, rsize_t s1max, const char * restrict s2, rsize_t n); | C11
errno_t strcat_s(char * restrict s1, rsize_t s1max, const char * restrict s2); | C11
errno_t strncat_s(char * restrict s1, rsize_t s1max, const char * restrict s2, rsize_t n); | C11
char *strtok_s(char * restrict s1, rsize_t * restrict s1max, const char * restrict s2, char ** restrict ptr); | C11
errno_t memset_s(void *s, rsize_t smax, int c, rsize_t n); | C11
errno_t strerror_s(char *s, rsize_t maxsize, errno_t errnum); | C11
size_t strerrorlen_s(errno_t errnum); | C11
size_t strnlen_s(const char *s, size_t maxsize); | C11

#B.24 Type-generic math <tgmath.h>

Name | C Version | Rust libc
-|
acos | C99 | N/A
sqrt | C99 | N/A
fmod | C99 | N/A
nextafter | C99 | N/A
asin | C99 | N/A
fabs | C99 | N/A
frexp | C99 | N/A
nexttoward | C99 | N/A
atan | C99 | N/A
atan2 | C99 | N/A
hypot | C99 | N/A
remainder | C99 | N/A
acosh | C99 | N/A
cbrt | C99 | N/A
ilogb | C99 | N/A
remquo | C99 | N/A
asinh | C99 | N/A
ceil | C99 | N/A
ldexp | C99 | N/A
rint | C99 | N/A
atanh | C99 | N/A
copysign | C99 | N/A
lgamma | C99 | N/A
round | C99 | N/A
cos | C99 | N/A
erf | C99 | N/A
llrint | C99 | N/A
scalbn | C99 | N/A
sin | C99 | N/A
erfc | C99 | N/A
llround | C99 | N/A
scalbln | C99 | N/A
tan | C99 | N/A
exp2 | C99 | N/A
log10 | C99 | N/A
tgamma | C99 | N/A
cosh | C99 | N/A
expm1 | C99 | N/A
log1p | C99 | N/A
trunc | C99 | N/A
sinh | C99 | N/A
fdim | C99 | N/A
log2 | C99 | N/A
carg | C99 | N/A
tanh | C99 | N/A
floor | C99 | N/A
logb | C99 | N/A
cimag | C99 | N/A
exp | C99 | N/A
fma | C99 | N/A
lrint | C99 | N/A
conj | C99 | N/A
log | C99 | N/A
fmax | C99 | N/A
lround | C99 | N/A
cproj | C99 | N/A
pow | C99 | N/A
fmin | C99 | N/A
nearbyint | C99 | N/A
creal | C99 | N/A

#B.25 Threads <threads.h>

Name | Rust libc
-|
thread_local | C11
once_flag | C11
ONCE_FLAG_INIT | C11
mtx_plain | C11
TSS_DTOR_ITERATIONS | C11
mtx_recursive | C11
cnd_t | C11
mtx_timed | C11
thrd_t | C11
thrd_timedout | C11
tss_t | C11
thrd_success | C11
mtx_t | C11
thrd_busy | C11
tss_dtor_t | C11
thrd_error | C11
thrd_start_t | C11
thrd_nomem | C11
void call_once(once_flag *flag, void (*func)(void)); | C11
int cnd_broadcast(cnd_t *cond); | C11
void cnd_destroy(cnd_t *cond); | C11
int cnd_init(cnd_t *cond); | C11
int cnd_signal(cnd_t *cond); | C11
int cnd_timedwait(cnd_t *restrict cond, mtx_t *restrict mtx, const struct timespec *restrict ts); | C11
int cnd_wait(cnd_t *cond, mtx_t *mtx); | C11
void mtx_destroy(mtx_t *mtx); | C11
int mtx_init(mtx_t *mtx, int type); | C11
int mtx_lock(mtx_t *mtx); | C11
int mtx_timedlock(mtx_t *restrict mtx, const struct timespec *restrict ts); | C11
int mtx_trylock(mtx_t *mtx); | C11
int mtx_unlock(mtx_t *mtx); | C11
int thrd_create(thrd_t *thr, thrd_start_t func, void *arg); | C11
thrd_t thrd_current(void); | C11
int thrd_detach(thrd_t thr); | C11
int thrd_equal(thrd_t thr0, thrd_t thr1); | C11
_Noreturn void thrd_exit(int res); | C11
int thrd_join(thrd_t thr, int *res); | C11
int thrd_sleep(const struct timespec *duration, struct timespec *remaining); | C11
void thrd_yield(void); | C11
int tss_create(tss_t *key, tss_dtor_t dtor); | C11
void tss_delete(tss_t key); | C11
void *tss_get(tss_t key); | C11
int tss_set(tss_t key, void *val); | C11

#B.26 Date and time <time.h>

Name | Rust libc
-|
NULL | C90
size_t | C90
struct timespec | C11
CLOCKS_PER_SEC | C90
clock_t | C90
struct tm | C90
TIME_UTC | C90
time_t | C90
clock_t clock(void); | C90
double difftime(time_t time1, time_t time0); | C90
time_t mktime(struct tm *timeptr); | C90
time_t time(time_t *timer); | C90
int timespec_get(timespec *ts, int base); | C11
char *asctime(const struct tm *timeptr); | C90
char *ctime(const time_t *timer); | C90
struct tm *gmtime(const time_t *timer); | C90
struct tm *localtime(const time_t *timer); | C90
size_t strftime(char * restrict s, size_t maxsize, const char * restrict format, const struct tm * restrict timeptr); | C90
_ _STDC_WANT_LIB_EXT1_ _ | C11
errno_t | C11
rsize_t | C11
errno_t asctime_s(char *s, rsize_t maxsize, const struct tm *timeptr); | C11
errno_t ctime_s(char *s, rsize_t maxsize, const time_t *timer); | C11
struct tm *gmtime_s(const time_t * restrict timer, struct tm * restrict result); | C11
struct tm *localtime_s(const time_t * restrict timer, struct tm * restrict result); | C11

#B.27 Unicode utilities <uchar.h>

Name | Rust libc
-|
mbstate_t | C95
size_t | C90
char16_t | C11
char32_t | C11
size_t mbrtoc16(char16_t * restrict pc16, const char * restrict s, size_t n, mbstate_t * restrict ps); | C11
size_t c16rtomb(char * restrict s, char16_t c16, mbstate_t * restrict ps); | C11
size_t mbrtoc32(char32_t * restrict pc32, const char * restrict s, size_t n, mbstate_t * restrict ps); | C11
size_t c32rtomb(char * restrict s, char32_t c32, mbstate_t * restrict ps); | C11

#B.28 Extended multibyte/wide character utilities <wchar.h>

Name | Rust libc
-|
wchar_t | C95
wint_t | C95
WCHAR_MAX | C95
size_t | C90
struct tm | C90
WCHAR_MIN | C95
mbstate_t | C95
NULL | C90
WEOF | C95
int fwprintf(FILE * restrict stream, const wchar_t * restrict format, ...); | C95
int fwscanf(FILE * restrict stream, const wchar_t * restrict format, ...); | C95
int swprintf(wchar_t * restrict s, size_t n, const wchar_t * restrict format, ...); | C95
int swscanf(const wchar_t * restrict s, const wchar_t * restrict format, ...); | C95
int vfwprintf(FILE * restrict stream, const wchar_t * restrict format, va_list arg); | C95
int vfwscanf(FILE * restrict stream, const wchar_t * restrict format, va_list arg); | C95
int vswprintf(wchar_t * restrict s, size_t n, const wchar_t * restrict format, va_list arg); | C95
int vswscanf(const wchar_t * restrict s, const wchar_t * restrict format, va_list arg); | C95
int vwprintf(const wchar_t * restrict format, va_list arg); | C95
int vwscanf(const wchar_t * restrict format, va_list arg); | C95
int wprintf(const wchar_t * restrict format, ...); | C95
int wscanf(const wchar_t * restrict format, ...); | C95
wint_t fgetwc(FILE *stream); | C95
wchar_t *fgetws(wchar_t * restrict s, int n, FILE * restrict stream); | C95
wint_t fputwc(wchar_t c, FILE *stream); | C95
int fputws(const wchar_t * restrict s, FILE * restrict stream); | C95
int fwide(FILE *stream, int mode); | C95
wint_t getwc(FILE *stream); | C95
wint_t getwchar(void); | C95
wint_t putwc(wchar_t c, FILE *stream); | C95
wint_t putwchar(wchar_t c); | C95
wint_t ungetwc(wint_t c, FILE *stream); | C95
double wcstod(const wchar_t * restrict nptr, wchar_t ** restrict endptr); | C95
float wcstof(const wchar_t * restrict nptr, wchar_t ** restrict endptr); | C95
long double wcstold(const wchar_t * restrict nptr, wchar_t ** restrict endptr); | C95
long int wcstol(const wchar_t * restrict nptr, wchar_t ** restrict endptr, int base); | C95
long long int wcstoll(const wchar_t * restrict nptr, wchar_t ** restrict endptr, int base); | C95
unsigned long int wcstoul(const wchar_t * restrict nptr, wchar_t ** restrict endptr, int base); | C95
unsigned long long int wcstoull(const wchar_t * restrict nptr, wchar_t ** restrict endptr, int base); | C95
wchar_t *wcscpy(wchar_t * restrict s1, const wchar_t * restrict s2); | C95
wchar_t *wcsncpy(wchar_t * restrict s1, const wchar_t * restrict s2, size_t n); | C95
wchar_t *wmemcpy(wchar_t * restrict s1, const wchar_t * restrict s2, size_t n); | C95
wchar_t *wmemmove(wchar_t *s1, const wchar_t *s2, size_t n); | C95
wchar_t *wcscat(wchar_t * restrict s1, const wchar_t * restrict s2); | C95
wchar_t *wcsncat(wchar_t * restrict s1, const wchar_t * restrict s2, size_t n); | C95
int wcscmp(const wchar_t *s1, const wchar_t *s2); | C95
int wcscoll(const wchar_t *s1, const wchar_t *s2); | C95
int wcsncmp(const wchar_t *s1, const wchar_t *s2, size_t n); | C95
size_t wcsxfrm(wchar_t * restrict s1, const wchar_t * restrict s2, size_t n); | C95
int wmemcmp(const wchar_t *s1, const wchar_t *s2, size_t n); | C95
wchar_t *wcschr(const wchar_t *s, wchar_t c); | C95
size_t wcscspn(const wchar_t *s1, const wchar_t *s2); | C95
wchar_t *wcspbrk(const wchar_t *s1, const wchar_t *s2); | C95
wchar_t *wcsrchr(const wchar_t *s, wchar_t c); | C95
size_t wcsspn(const wchar_t *s1, const wchar_t *s2); | C95
wchar_t *wcsstr(const wchar_t *s1, const wchar_t *s2); | C95
wchar_t *wcstok(wchar_t * restrict s1, const wchar_t * restrict s2, wchar_t ** restrict ptr); | C95
wchar_t *wmemchr(const wchar_t *s, wchar_t c, size_t n); | C95
size_t wcslen(const wchar_t *s); | C95
wchar_t *wmemset(wchar_t *s, wchar_t c, size_t n); | C95
size_t wcsftime(wchar_t * restrict s, size_t maxsize, const wchar_t * restrict format, const struct tm * restrict timeptr); | C95
wint_t btowc(int c); | C95
int wctob(wint_t c); | C95
int mbsinit(const mbstate_t *ps); | C95
size_t mbrlen(const char * restrict s, size_t n, mbstate_t * restrict ps); | C95
size_t mbrtowc(wchar_t * restrict pwc, const char * restrict s, size_t n, mbstate_t * restrict ps); | C95
size_t wcrtomb(char * restrict s, wchar_t wc, mbstate_t * restrict ps); | C95
size_t mbsrtowcs(wchar_t * restrict dst, const char ** restrict src, size_t len, mbstate_t * restrict ps); | C95
size_t wcsrtombs(char * restrict dst, const wchar_t ** restrict src, size_t len, mbstate_t * restrict ps); | C95
_ _STDC_WANT_LIB_EXT1_ _ | C11
errno_t | C11
rsize_t | C11
int fwprintf_s(FILE * restrict stream, const wchar_t * restrict format, ...); | C11
int fwscanf_s(FILE * restrict stream, const wchar_t * restrict format, ...); | C11
int snwprintf_s(wchar_t * restrict s, rsize_t n, const wchar_t * restrict format, ...); | C11
int swprintf_s(wchar_t * restrict s, rsize_t n, const wchar_t * restrict format, ...); | C11
int swscanf_s(const wchar_t * restrict s, const wchar_t * restrict format, ...); | C11
int vfwprintf_s(FILE * restrict stream, const wchar_t * restrict format, va_list arg); | C11
int vfwscanf_s(FILE * restrict stream, const wchar_t * restrict format, va_list arg); | C11
int vsnwprintf_s(wchar_t * restrict s, rsize_t n, const wchar_t * restrict format, va_list arg); | C11
int vswprintf_s(wchar_t * restrict s, rsize_t n, const wchar_t * restrict format, va_list arg); | C11
int vswscanf_s(const wchar_t * restrict s, const wchar_t * restrict format, va_list arg); | C11
int vwprintf_s(const wchar_t * restrict format, va_list arg); | C11
int vwscanf_s(const wchar_t * restrict format, va_list arg); | C11
int wprintf_s(const wchar_t * restrict format, ...); | C11
int wscanf_s(const wchar_t * restrict format, ...); | C11
errno_t wcscpy_s(wchar_t * restrict s1, rsize_t s1max, const wchar_t * restrict s2); | C11
errno_t wcsncpy_s(wchar_t * restrict s1, rsize_t s1max, const wchar_t * restrict s2, rsize_t n); | C11
errno_t wmemcpy_s(wchar_t * restrict s1, rsize_t s1max, const wchar_t * restrict s2, rsize_t n); | C11
errno_t wmemmove_s(wchar_t *s1, rsize_t s1max, const wchar_t *s2, rsize_t n); | C11
errno_t wcscat_s(wchar_t * restrict s1, rsize_t s1max, const wchar_t * restrict s2); | C11
errno_t wcsncat_s(wchar_t * restrict s1, rsize_t s1max, const wchar_t * restrict s2, rsize_t n); | C11
wchar_t *wcstok_s(wchar_t * restrict s1, rsize_t * restrict s1max, const wchar_t * restrict s2, wchar_t ** restrict ptr); | C11
size_t wcsnlen_s(const wchar_t *s, size_t maxsize); | C11
errno_t wcrtomb_s(size_t * restrict retval, char * restrict s, rsize_t smax, wchar_t wc, mbstate_t * restrict ps); | C11
errno_t mbsrtowcs_s(size_t * restrict retval, wchar_t * restrict dst, rsize_t dstmax, const char ** restrict src, rsize_t len, mbstate_t * restrict ps); | C11
errno_t wcsrtombs_s(size_t * restrict retval, char * restrict dst, rsize_t dstmax, const wchar_t ** restrict src, rsize_t len, mbstate_t * restrict ps); | C11

#B.29 Wide character classification and mapping utilities <wctype.h>

Name | C Version | Rust libc
-|
wint_t | C95
wctrans_t | C95
wctype_t | C95
WEOF | C95
int iswalnum(wint_t wc); | C95
int iswalpha(wint_t wc); | C95
int iswblank(wint_t wc); | C99
int iswcntrl(wint_t wc); | C95
int iswdigit(wint_t wc); | C95
int iswgraph(wint_t wc); | C95
int iswlower(wint_t wc); | C95
int iswprint(wint_t wc); | C95
int iswpunct(wint_t wc); | C95
int iswspace(wint_t wc); | C95
int iswupper(wint_t wc); | C95
int iswxdigit(wint_t wc); | C95
int iswctype(wint_t wc, wctype_t desc); | C95
wctype_t wctype(const char *property); | C95
wint_t towlower(wint_t wc); | C95
wint_t towupper(wint_t wc); | C95
wint_t towctrans(wint_t wc, wctrans_t desc); | C95
wctrans_t wctrans(const char *property); | C95
