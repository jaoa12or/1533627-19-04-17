1533627-19-04-17

export contar=$(ps -A | wc -l)


echo $((2**4))


export contar=$(ps -A | tail -n +2 | wc -l)

echo $contar
