# POV-Ray-matrices
POV-Ray include file for working with matrices

## M_NoOfRows(AA)

#### Example:

```
#declare N =
    M_NoOfRows(
        array[3][4] {
            {  2.0,  4.0,  5.0,  4.0 },
            { -4.0,  7.0, -2.0, -0.5 },
            {  1.0,  3.0,  1.0,  0.0 }
        }
    )
;

#debug str(N, 0, 0)
```

#### Result:

```
3
```

## M_NoOfCols(AA)

#### Example:

```
#declare N =
    M_NoOfCols(
        array[3][4] {
            {  2.0,  4.0,  5.0,  4.0 },
            { -4.0,  7.0, -2.0, -0.5 },
            {  1.0,  3.0,  1.0,  0.0 }
        }
    )
;

#debug str(N, 0, 0)
```

#### Result:

```
4
```

## M_NoOfRowsStr(AA)

```
#declare S =
    M_NoOfRowsStr(
        array[3][4] {
            {  2.0,  4.0,  5.0,  4.0 },
            { -4.0,  7.0, -2.0, -0.5 },
            {  1.0,  3.0,  1.0,  0.0 }
        }
    )
;

#debug S
```

#### Result:

```
3
```

## M_NoOfColsStr(AA)

#### Example:

```
#declare S =
    M_NoOfColsStr(
        array[3][4] {
            {  2.0,  4.0,  5.0,  4.0 },
            { -4.0,  7.0, -2.0, -0.5 },
            {  1.0,  3.0,  1.0,  0.0 }
        }
    )
;

#debug S
```

#### Result:

```
4
```

## M_SizeStr(AA)

## M_PrintSize(AA)

## M_CustomStr(AA, L, P, Compact)

## M_Str(AA)

## M_CustomPrint(AA, L, P, Compact)

## M_Print(AA)

## M_Zero(SizeI, SizeJ)

## M_Constant(SizeI, SizeJ, Const)

## M_Identity(Size)

## M_Neg(AA)

## M_Pos(AA)

## M_Scale(AA, Scale)

## M_ApplyCheckerSigns(AA)

## M_ScaleRow(AA, RowNo, Scale)

## M_ScaleCol(AA, ColNo, Scale)

## M_Transpose(AA)

## M_SwapRows(AA, RowNo, Row_No)

## M_SwapCols(AA, ColNo, Col_No)

## M_Add(AA, BB)

## M_Sub(AA, BB)

## M_Trace(AA)

## M_Mult(AA, BB)

## M_DelRow(AA, RowNo)

## M_DelCol(AA, ColNo)

## M_DelRowAndCol(AA, RowNo, ColNo)

## M_AddScaledRowToRow(AA, Scale, RowNo, ToRowNo)

## M_AddScaledColToCol(AA, Scale, ColNo, ToColNo)

## M_SubMatrix(AA, RowNo, NoOfRows, ColNo, NoOfCols)

## M_Stack(AAAA)

## M_Det_11(AA)

## M_Det_22(AA)

## M_Det_33(AA)

## M_Det_44(AA)

## M_Det_55(AA)

## M_Det_66(AA)

## M_Det_SS(AA)

## M_Det(AA)

## M_Minors(AA)

## M_Cofactors(AA)

## M_Adjoint(AA)

## M_Inv_11(AA)

## M_Inv_22(AA)

## M_Inv_33(AA)

## M_Inv_44(AA)

## M_Inv_SS(AA)

## M_Inv(AA)

## M_FromTransformFn(TransformFn)

## M_FromTransform(Transform)

## M_RowFromPosition2D(p0)

## M_ColFromPosition2D(p0)

## M_RowFromVector2D(v0)

## M_ColFromVector2D(v0)

## M_RowFromPosition3D(p0)

## M_ColFromPosition3D(p0)

## M_RowFromVector3D(v0)

## M_ColFromVector3D(v0)

## M_SkewFromVector3D(v0)

## M_Position2D_FromRow(AA, RowNo)

## M_Position2D_FromCol(AA, ColNo)

## M_Vector2D_FromRow(AA, RowNo)

## M_Vector2D_FromCol(AA, ColNo)

## M_Position3D_FromRow(AA, RowNo)

## M_Position3D_FromCol(AA, ColNo)

## M_Vector3D_FromRow(AA, RowNo)

## M_Vector3D_FromCol(AA, ColNo)
